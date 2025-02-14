# RESTful API with Node.js, Express, and MongoDB

## Project Setup

### Prerequisites
- Node.js installed
- MongoDB instance (local or MongoDB Atlas)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/restful-api-node.git
   cd restful-api-node
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add your MongoDB connection string:
   ```sh
   MONGO_URI=your_mongodb_connection_string
   ```
4. Start the server:
   ```sh
   npm start
   ```

## API Endpoints

### Get all items
```http
GET /items
```

### Create a new item
```http
POST /items
```
#### Request Body
```json
{
  "name": "Item Name",
  "description": "Item Description"
}
```

### Update an item
```http
PATCH /items/:id
```

### Delete an item
```http
DELETE /items/:id
```

## Documentation
The API documentation is available on Postman: [https://documenter.getpostman.com/view/41795951/2sAYXECcy](#)



