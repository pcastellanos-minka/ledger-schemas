### Definición de valores de charge
| CodeName | Name | Definition |
|----------|------|------------|
| DEBT | BorneByDebtor | Todos los gastos de transacción correrán a cargo del deudor. |
| CRED | BorneByCreditor | Todos los gastos de transacción correrán a cargo del acreedor. |
| SHAR | Shared | En un contexto de transferencia de crédito, significa que los cargos de transacción del lado del remitente correrán a cargo del deudor, mientras que los cargos de transacción del lado del receptor correrán a cargo del acreedor.<br><br>En un contexto de débito directo, significa que los cargos de transacción en el lado del remitente correrán a cargo del acreedor, los cargos de transacción en el lado del receptor correrán a cargo del deudor. |
| SLEV | FollowingServiceLevel | Los cargos se aplicarán siguiendo las reglas acordadas en el nivel y/o esquema de servicio. |


### Definición de valores del tipo de cuenta
| CodeName | Intent map | Name | Definition |
|----------|------------|------|------------|
| CAHO | svgs | SavingsAccounts | Cuentas de ahorro |
| CCTE | cacc | CurrentAccounts | Cuentas corrientes |
| DBMO |  | LowAmountDeposits | Depósitos de bajo monto |
| DORD |  | OrdinaryDeposits | Depósitos ordinarios |
| DBMI |  | InclusiveSmallDeposits | Depósitos de bajo monto inclusivos |

### Definición de valores del tipo de documento (IdType)
| CodeName | Intent map | Name |
|----------|------------|------|
| CC | nidn | Cédula de ciudadanía |
| CE | arnu | Cédula de extranjería |
| NUIP |  | Número Único de Identificación Personal (NUIP) |
| PPT |  | Permiso de Protección Temporal (PPT) |
| NIT | txid | Número de Identificación Tributaria sin dígito de verificación |
| PEP |  | Permiso Especial de Permanencia |
| PAS | ccpt | Pasaporte |
| OTR | othr  | Otro |

### Definición de valores de SPBVI (spbviTarget y spbviSource)
| ClearingSystemCode | CodeName | Name | Definition |
|---------------------|----------|------|------------|
| TFY | Transifya | Transifya | Sistema de Pago de Bajo Valor Inmediato |
| ENT | Entrecuentas | Entrecuentas | Sistema de Pago de Bajo Valor Inmediato |
| VIS | Visionamos | Visionamos | Sistema de Pago de Bajo Valor Inmediato |