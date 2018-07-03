# Setup

elasticsearch
{
  "settings": {
    "number_of_shards": 5,
    "index": {
      "mapping.total_fields.limit": "900000",
      "mapping.nested_fields.limit": "10000"
    }
  }
}
