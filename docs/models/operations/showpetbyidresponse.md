# ShowPetByIDResponse


## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `HTTPMeta`                                                         | [components.HTTPMetadata](../../models/components/httpmetadata.md) | :heavy_check_mark:                                                 | N/A                                                                |
| `Pet`                                                              | [*components.Pet](../../models/components/pet.md)                  | :heavy_minus_sign:                                                 | Expected response to a valid request                               |
| `Error`                                                            | [*components.Error](../../models/components/error.md)              | :heavy_minus_sign:                                                 | unexpected error                                                   |