
# Use Cases

## Register/Login
- **Actor:** User
- **Trigger:** User submits credentials
- **Outcome:** JWT token is returned; user is redirected to /dashboard

## Create Design
- **Actor:** User
- **Trigger:** Click on "New Design"
- **Outcome:** Canvas is loaded; user can draw/upload

## Save Design
- **Actor:** User
- **Trigger:** Click "Save"
- **Outcome:** Design JSON is saved to MongoDB

## Export Design
- **Actor:** User
- **Trigger:** Click "Export"
- **Outcome:** PNG/PDF download is triggered
