
# SnifferAPI

Getting data from tokensniffer.com
## API Reference

#### Base URL : ```api.snifferapi.com```

#### Get new tokens

```http
GET /newtokens
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `apikey`  | `string` | **Required**. Your API key |
| `maxshow` | `int` | *Recommended*. The nb of tokens to get |

#### Get trending tokens

```http
GET /trendingtokens
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `apikey`  | `string` | **Required**. Your API key |
| `maxshow` | `int` | *Recommended*. The nb of tokens to get |

#### Get top tokens

```http
GET /toptokens
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `apikey`  | `string` | **Required**. Your API key |
| `maxshow` | `int` | *Recommended*. The nb of tokens to get |

#### Get scam tokens

```http
GET /scamtokens
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `apikey`  | `string` | **Required**. Your API key |
| `maxshow` | `int` | *Recommended*. The nb of tokens to get |

#### Get token (score and infos)

```http
GET /token/${address}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `apikey`  | `string` | **Required**. Your API key        |
| `address` | `string` | **Required**. address of the token to fetch |
