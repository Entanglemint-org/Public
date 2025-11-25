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
| Quantis PCIe-240M   | F8D5801639FAB63C-2A88F3413949316E-0000000240               |
| Quantis PCIe-40M    | F8D5801639FAB63C-2A88F3413949316E-0000000040               |
| Quantis QRNG USB    | F8D5801639FAB63C-2A88F3413949316E-0000000004               |

## Outcome Target Checks

### 0000000240
```
F8D5801639FAB63C185C0CDABF5E37699C37A0E5115406A73DE6DAB2530B86A7C8B7F24A1354C768C414434A92F7185C5B9AB025AF5BBFA62A88F3413949316E
```

### 0000000040
```
F8D5801639FAB63C185C0CDABF5E37699C37A0E5115406A73DE6DAB2530B86A7C8B7F24A1354C768C414434A92F7185C5B9AB025AF5BBFA62A88F3413949316E
```

### 0000000004
```
F8D5801639FAB63C185C0CDABF5E37699C37A0E5115406A73DE6DAB2530B86A7C8B7F24A1354C768C414434A92F7185C5B9AB025AF5BBFA62A88F3413949316E
```

