
# FoodDoof : Your Recipe Jar

Fooddoof is a recipe management web application designed to provide users with an intuitive and engaging platform to explore, create, and manage recipes. With Fooddoof, users can browse a diverse collection of recipes, create their own customized recipes, and even modify recipe quantities based on the number of people they are serving. Each recipe includes step-by-step directions to ensure seamless cooking experiences. Additionally, users can bookmark their favorite recipes for easy access, and any recipe they create is automatically bookmarked for convenience. Fooddoof makes cooking easy, personalized, and fun!
## API Reference

#### Get all items

```http
  GET https://forkify-api.herokuapp.com/api/v2/recipes
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET https://forkify-api.herokuapp.com/api/v2/recipes/{:id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


## Deployment

To deploy this project run

```bash
  npm install
  npm run start
```


## 🚀 About Me
I'm a full stack developer...


## Authors

- [@nishantatras](https://www.github.com/nishantatras)

