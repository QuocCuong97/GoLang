# Cài đặt Golang
## **1) Cài đặt trên Linux**
- **B1 :** Download file cài đặt :
    ```
    # wget https://golang.org/dl/go1.15.6.linux-amd64.tar.gz
    ```
- **B2 :** Giải nén file cài đặt :
    ```
    # tar -C /usr/local -xzf go1.15.6.linux-amd64.tar.gz
    ```
- **B3 :** Add binary `/usr/local/go/bin` vào PATH của OS :
    ```
    # export PATH=$PATH:/usr/local/go/bin
    ```
- **B4 :** Kiểm tra lại phiên bản Go đã cài đặt :
    ```
    # go version
    ```
    => Output :
    ```
    go version go1.15.5 linux/amd64
    ```