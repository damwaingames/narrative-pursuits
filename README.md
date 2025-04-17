# Narrative Pursuits

A REST and GraphQL api driven online service for running narrative roleplaying games.


![GitHub License](https://img.shields.io/github/license/damwaingames/narrative-pursuits)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/damwaingames/narrative-pursuits)



## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@damwaingames](https://www.github.com/damwaingames)


## Demo

Insert gif or link to demo