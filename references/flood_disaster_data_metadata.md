| Nome da variável                    | Tipo                       | Descrição                                              | Unidades   | Valores faltantes   |
|:------------------------------------|:---------------------------|:-------------------------------------------------------|:-----------|:--------------------|
| segment_id                          | Numérico/Texto (SEG-00001) | Identificador único de cada segmento                   | -          | Não                 |
| city_name                           | Categórico                 | Nome da cidade onde o dado foi coletado                | -          | Não                 |
| admin_ward                          | Categórico                 | Divisão administrativa da cidade                       | -          | Não                 |
| latitude                            | Numérico (float)           | Latitude do ponto                                      | graus      | Não                 |
| longitude                           | Numérico (float)           | Longitude do ponto                                     | graus      | Não                 |
| catchment_id                        | Numérico/Texto (CAT-136)   | Identificador da bacia de drenagem                     | -          | Não                 |
| elevation_m                         | Numérico (float)           | Elevação do terreno                                    | m          | Sim                 |
| land_use                            | Categórico                 | Uso do solo na área (residencial, comercial etc.)      | -          | Não                 |
| soil_group                          | Categórico                 | Tipo ou classificação do solo                          | -          | Sim                 |
| drainage_density_km_per_km2         | Numérico (float)           | Densidade de drenagem                                  | km/km²     | Sim                 |
| storm_drain_proximity_m             | Numérico (float)           | Distância até o ponto de drenagem pluvial mais próximo | m          | Sim                 |
| storm_drain_type                    | Categórico                 | Tipo de infraestrutura de drenagem pluvial             | -          | Sim                 |
| historical_rainfall_intensity_mm_hr | Numérico (float)           | Intensidade histórica de chuva                         | mm/h       | Não                 |
| return_period_years                 | Numérico (Int)             | Período de retorno de eventos extremos                 | anos       | Não                 |
| risk_labels                         | Categórico                 | Rótulo de risco de inundação                           | -          | Não                 |