# API
Available endpoints:
- `GET /api/v1/lead` - Get all lead
- `GET /api/v1/lead/id` - Get lead by id
- `POST /api/v1/lead` - Create new lead
- `DELETE /api/v1/lead/id` - Delete lead by id

Example of request body for `POST /api/v1/lead`:
```json
{
  "name": "John Doe",
  "email": "johhdoe@gmail.com
}