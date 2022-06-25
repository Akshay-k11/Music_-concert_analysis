
# Data analysis on music dataset

A brief description of what this project does and who it's for
Project is to explore the data using pandas and sql and to learn data wrangling, data analysis and answer some important questions that will help to organize an music event in coming future.


## Acknowledgements

Data source - https://www.kaggle.com/datasets/samaxtech/chinook-music-store-data
## Documentation

Few questions that will be answered using querry in sql and pandas

1. list the customers that are from brazil and USA 
2. list the Employees who are Sales Agents
3. list the invoices associated with each sales agent. The resultant table should include the Sales Agent's full name
4. Which country has most number of invoices?
5. Which city has the best customers? 
6. what is people's favourite Genre?
7. Get email ids of the people who like rock music
8. Who is writing the rock music?
9. Revenue for the artist
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

