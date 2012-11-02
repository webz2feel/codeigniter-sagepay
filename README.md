# SAGEPAY payment gateway integration for CodeIgniter

### AUTHOR
Miguel Guerreiro

### VERSION
0.5

### HOW TO INSTALL
1. Copy the structure into your CI installation
2. Register with SagePay for a developer account
3. Edit the config file (notes inside)
4. Load the library and start using it

### LIST OF FUNCTIONS:
~~~
  ->txPayment       register a transaction
  ->txAuthorize     register a transaction (authorize only)
  ->txRelease       release an already registered transaction (through txAuthorize)
  ->txRepeat        register a repeated transaction
  ->txRefund        refund an already registered transaction
  ->txDirectRefund  issue a direct refund
  ->txManual        register a transaction manually
  ->txCancel        cancel an already registered transaction
  ->txAbort         abort an already registered transaction
  ->txVoid          void an already registered transation
~~~