# Quantum Setup

**Supported Devices:**  
- Quantis PCIe-240M  
- Quantis PCIe-40M  
- Quantis QRNG USB  

## Requirements

- Supported Quantis hardware installed and operational  
- gcc (GNU C Compiler)  
- libc (GNU C Library)  
- Make  
- libcurl-dev  
- Python  
- Entanglemint-libqrng-PCI library  

## Work Unit Selection

| Device              | Work Unit ID                                               |
|---------------------|------------------------------------------------------------|
| Quantis PCIe-240M   | E12EF23728F9AF12-57A925C917F96449-0000000240               |
| Quantis PCIe-40M    | E12EF23728F9AF12-57A925C917F96449-0000000040               |
| Quantis QRNG USB    | E12EF23728F9AF12-57A925C917F96449-0000000004               |

## Outcome Target Checks

### 0000000240
```
E12EF23728F9AF12F3ADFF999FACC1466EE5A653622681282E864F32DD162A5F183559865D12D0215C9BCE72AD1A0BB710F4630A5A141DD057A925C917F96449
```

### 0000000040
```
E12EF23728F9AF12F3ADFF999FACC1466EE5A653622681282E864F32DD162A5F183559865D12D0215C9BCE72AD1A0BB710F4630A5A141DD057A925C917F96449
```

### 0000000004
```
E12EF23728F9AF12F3ADFF999FACC1466EE5A653622681282E864F32DD162A5F183559865D12D0215C9BCE72AD1A0BB710F4630A5A141DD057A925C917F96449
```

