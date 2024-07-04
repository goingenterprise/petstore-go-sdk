# ListPetsResponse


## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `HTTPMeta`                                                         | [components.HTTPMetadata](../../models/components/httpmetadata.md) | :heavy_check_mark:                                                 | N/A                                                                |
| `Pets`                                                             | [][components.Pet](../../models/components/pet.md)                 | :heavy_minus_sign:                                                 | A paged array of pets                                              |
| `Error`                                                            | [*components.Error](../../models/components/error.md)              | :heavy_minus_sign:                                                 | unexpected error                                                   |
| `Headers`                                                          | map[string][]*string*                                              | :heavy_check_mark:                                                 | N/A                                                                |