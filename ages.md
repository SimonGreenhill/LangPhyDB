# Age Specifications

Ages are specified in the following ways:

|----------------------------------------------------------|------------------------------------------------|
| Type                                                     |  Specification                                 |
|----------------------------------------------------------|------------------------------------------------|
| Point Value:                                             |  $value                                        |
| Upper Boundary:                                          |  <$value                                       |
| Lower Boundary:                                          |  >$value                                       |
| Uniform Range:                                           |  uniform($lower, $upper)                       |
| Mean and Standard Deviation                              |  $mean±$sd                                     |
| Normal Distribution:                                     |  normal($mean, $sd)                            |
| Lognormal Distribution:                                  |  lognormal($m, $sd, $offset, realspace=false)  |
| Lognormal Distribution Realspace:                        |  lognormal($m, $sd, $offset, realspace=true)   |
| Reverse Lognormal Distribution:                          |  revlognormal($m, $sd, $offset)                |
| Highest Posterior Density Interval: 95%                  |  hpd($mean, $lower, $upper)                    |
| Highest Posterior Density Interval: 89%                  |  hpd89($mean, $lower, $upper)                  |
| Highest Posterior Density Interval: range reported only  |  hpd95rangeonly($lower, $upper)                |
| Unknown                                                  |  unknown($text)                                |
| Exponential                                              |  exponential($lambda, $offset)                 |
| Gamma                                                    |  gamma($alpha, $beta, $offset)                 |
|----------------------------------------------------------|------------------------------------------------|
