# yiban-auto
csust易班校本化自动健康打卡.

## Usage
### 1. edit the config.json
```
{
    "UserInfo": {
        "NickName": "nickname",
        "Mobile": "mobile",
        "Password": "password"
    }

    "27a2a4cdf16a8c864daca54a00c4db03": {
        "name": "detail_address",
        "location": "longitude,latitude",
        "address": "address"
    }
}
```
### 2. run program
```
pip install -r requirements.txt
python main.py
```

## Reference
- [Sricor/Yiban](https://github.com/Sricor/Yiban)
- [apecodex/yibanAutoSgin](https://github.com/apecodex/yibanAutoSgin)

## License
Distributed under the **Apache-2.0 License**. See [LICENSE](LICENSE) for more information.