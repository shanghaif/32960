# 心跳

## 用例 1

### 原始报文

```sh
232307FE4C57584353323031373131303730303030010000A8
```

### 解析结果

```json
{ 
    "clientId": 36, 
    "commandIDHex": "07", 
    "requestId": "tjgeio2jye", 
    "vin": "LWXCS201711070000" }
```

### 发送

```
232307014C5758435332303137313130373030303001000057
```

## 用例 2

### 原始报文

```sh
232307FE0000000000000000000000000000000000010000F8
```

### 解析结果

```json
{
  "clientId": 9,
  "commandIDHex": "07",
  "platform": "shenlong",
  "requestId": "3nx34zak19b",
  "vin": ""
}
```

### 发送

```
23230701000000000000000000000000000000000001000007
```

## 用例 3

### 原始报文

```sh
232307FE0000000000000000000000000000000000010000F8
```

### 解析结果

```json
{
  "clientId": 1,
  "commandIDHex": "07",
  "platform": "wanxiang",
  "requestId": "vf8xsujcr9h",
  "vin": ""
}
```

### 发送

```
23230701000000000000000000000000000000000001000007
```