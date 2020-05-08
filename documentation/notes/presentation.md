# Introductions (TJ)

- Set A
- James, Eric, Peter, Kaiyuan, TJ, Sebastian
- Tech used
  - Backend
    - Egg js, framework based on Koa (a framework created by the same people who made express)
    - MongoDB
    - Dockerized
  - Frontend
    - ReactJS
    - Material UI Components
    - react-router
    - react-hook-form for validation

# Kiosk (Sebastian)

- Reason for two frontend applications
- Clinics need to log in to get a personalized check in app
- Login (collingwood, password)
- Welcome Screen
  - Personalized welcome message
- Appointment selection
  - Ordered by start time
  - Displays all appointments +/- 15 from current time
- Check In
  - Form validation
  - Auto complete is disabled on these inputs for privacy
  - ```json
    "familyName": "Pelletier",
    "givenName": "Lucas",
    "birthday": {
      "$date": "2001-03-17T00:00:00.000Z"
    },
    "address": {
      "_id": {
        "$oid": "5eb59ed958513e0045d6c133"
      },
      "street": "8291 Bay Ave",
      "city": "Trenton",
      "province": "NB",
      "country": "Canada",
      "postcode": "J2M 8C2"
    },
    "phone": "189 711 3966",
    "healthId": "1111 111 111",
    ```
  - Example with wrong information
  - Submit correct information
- Show that user no longer shows up on appointment screen
- Clear cookies and log in to other clinic (sunrise, password)
  - Logout was disabled on kiosk to prohibit patient access
  - Show welcome screen change
  - Show that upcoming appointments are not the same

# Clinic Admin (Peter)

- Login (sunrise, password)

- Show responsiveness

- Kiosk Config

  - Default is Last Name/Birthday
  - Show validation when no fields are selected
  - Change the selected form fields
  - Save preferences (snackbar notification displays)
  - Show updated form on sunrise kiosk

- Appointment List
  - Pagination
  - Search by date/time
  - search by start time

# Porton Admin (Eric)

- Because of the different role, sidebar options have changed
- Clinic List
  - Enable/Disable clinic (sunrise)
  - Logout and attempt to login as sunrise admin
  - Show the same behavior on the kiosk side (does this work)

# Final Close (James)

- Thanks to Porton for partnering with BCIT for this project and offering their guidance on a weekly basis
- Thanks to Phil for managing the program during these turbulent times
