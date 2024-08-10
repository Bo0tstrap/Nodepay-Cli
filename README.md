# Kurulum Talimatları

1. Paket listelerini güncelleyin:

    ```bash
    sudo apt update
    ```

2. `curl` paketini yükleyin:

    ```bash
    sudo apt install curl -y
    ```

3. `nodepay_setup.sh` scriptini indirin:

    ```bash
    curl -O https://gist.githubusercontent.com/Bo0tstrap/479627be43db165b4016291ff76ea2f1/raw/03168fe8d56d69d3c3dc2809a38582e822b4979c/nodepay_setup.sh
    ```

4. İndirilen script dosyasına çalıştırılabilir izin verin:

    ```bash
    chmod +x nodepay_setup.sh
    ```

5. Yeni bir `screen` oturumu başlatın:

    ```bash
    screen -S nodepay
    ```

6. Scripti belirttiğiniz URL ile çalıştırın:

    ```bash
    ./nodepay_setup.sh
    ```

Bu talimatları GitHub deposunun `README.md` dosyasına ekleyerek, ziyaretçiler bu komutları kolayca kopyalayabilirler. Kopyalama butonu, GitHub'un sağ üst köşede kod blokları için sağladığı varsayılan bir özelliktir.
