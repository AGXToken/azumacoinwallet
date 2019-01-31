**1. Clone wallet sources**

```
git clone --recursive https://github.com/AGXToken/azumacoinwallet.git
```

**2. Modify `AzumacoinWallet.cmake`**
 
```
set(CN_PROJECT_NAME "furiouscoin")
set(CN_CURRENCY_DISPLAY_NAME "FuriousCoin")
set(CN_CURRENCY_TICKER "XFC")
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
