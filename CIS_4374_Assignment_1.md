```
Name: Mariam Alabi
Course Name: CIS 4374
Instructor: Professor Dobretsberger
Date: 9/10/26
```

```
Assignment 1
```

```
Task 1:
```

```
Research: What already exists? Add the existing software landscape to your
document, and how your application will be different from what already exists
```

# `My response:` 

```
A parking app that already exists is the ParkMobile app. The ParkMobile app
allows a driver to find and pay for parking on the app. While looking at the
app, I noticed that a driver only has access to the location of where they want
to park, but not the parking spot when they have arrived at their destination. I
believe that my application will be better from the Parkmobile app because my
application will allow drivers to reserve a particular spot for when the driver
arrives.
```

# `Task 2:` 

```
Start vision and scope section: Start with how the this project was acquired
introduction of your (fictional company, and rough overview of what this project
is about
```

# `My response:` 

```
The Smart Parking Platform was acquired after identifying the needs of finding
parking for the drivers. The key goal of this project is to satisfy the users
that are in need of finding available parking, reserve parking spots, and paying
for the parking space. This project will also benefit the parking operators by
helping them keep track of the amount of parking spaces being used.
```

# `Task 3:` 

```
Deliver a draft for the SRS, including 15 user stories (minimum). This should
grow over the course of the semester to completion.
```

```
1.)User registration and authentication
```

# `Actor: Driver` 

```
Purpose: The driver needs to create an account before reserving a parking spot.
```

```
Steps:
```

- `The driver would need to create an account to log into the app (email,` 

- `password, and vehicle information).` 

- `The system would now send a verification code.` 

- `The driver then uses the code to complete registration and log in.` 

# `2.) Real-time parking space availability` 

# `Actor: Driver` 

```
Purpose: Showing the drivers the available and occupied parking spots
```

```
Steps:
```

- `The driver would need to select which parking garage that they would want` 

- `to go to.` 

- `The app will then check the real-time information from the sensors to see` 

- `which parking spaces are available or occupied.` 

- `The app will show the driver the available spots that are green and the` 

- `occupied spots that are red.` 

- `3.) Interactive map displaying available parking locations` 

# `Actor: Driver` 

```
Purpose: The drivers are provided with a layout of the parking garage
```

```
Steps:
```

- `The driver looks in the app to find the parking garage that he/she wants.` 

- `The driver selects which floor level they would like to view` 

- `The app shows where to drive and which parking spaces are available.` 

# `4.) Parking reservation capability` 

```
Actor: Driver
```

```
Purpose: The drivers are reserving a specific parking spot before arrival
```

```
Steps:
```

- `The driver selects an open spot on the floor map.` 

- `The driver clicks on â€œReserve Spot.â€ �` 

- `The system sets a 25 minute time period so no other drivers can claim it.` 

# `5.) Digital payment processing` 

# `Actor: Driver` 

```
Purpose: Allowing the drivers to park for their parking ticket.
```

```
Steps:
```

- `The driver opened the payment checkout section` 

- `The driver then selects a payment method` 

- `The system processes the transaction and sends them an email confirmation` 

- `code.` 

# `6.) Reservation history and receipts` 

# `Actor: Driver` 

```
Purpose: The driver is able to view past parking history and view past receipts.
```

```
Steps:
```

- `The driver clicks on the "Reservation Historyâ€ tab to review their past �` 

- `transactions.` 

- `The system shows the driver the list of past parking visits.` 

- `The driver can view any past visits and download their receipts.` 

# `7.) Administrative dashboard for parking operators` 

# `Actor: Parking Operators` 

```
Purpose: Parking Operators are able to manage their parking garage.
```

```
Steps:
```

- `The Parking is able to log into the system` 

- `They can select their registered facility` 

- `The system shows all the data for the parking spaces, prices, and other` 

- `facility utilities.` 

# `8.) Occupancy reporting and analytics` 

```
Actor: Parking Operator
Purpose: The parking Operators
```

```
Steps:
```

- `The Parking operator views the â€œAnalyticsâ€ section on the dashboard. �` 

- `- The system will now display a chart showing the daily activity.` 

- `- The Parking operator can choose to view information at any time period` 

- `(day, week, month, and year).` 

# `9.) Notifications and alerts for users` 

# `Actor: Driver` 

```
Purpose: Alerting the drivers on when their parking time is close to expiring.
```

```
Steps:
```

- `Once the driver has reserved a parking spot, the system then starts a 25-` 

- `minute countdown timer for the driver to arrive.` 

- `The system then notifies the driver 25-minutes before the time expires.` 

- `- The driver has the option to extend the parking reservation.` 

# `10.) Integration with external mapping/navigation services` 

```
Actor: Driver
```

```
Purpose: The app provides the driver direction.
```

```
Steps:
```

- `On the app the driver clicks on â€œNavigateâ€ to know where the drivers �` 

- `are heading to.` 

- `The app is then provided with a GPS so that the driver can know where the` 

- `garage entrances are.` 

- `Once the driver enters the garage, the app will then explain the` 

- `directions on where to go and find the reserved parking spot` 

# `11.) Dynamic pricing rules/ events` 

```
Actor: Parking operator
```

```
Purpose: The parking prices increase during busy events
```

```
Steps:
```

- `The parking operators when the parking prices increase or decrease` 

- `The system monitors how occupied the parking garage gets during busy hours` 

- `(busy events).` 

- 

   - `The app will show the drivers the updated prices.` 

- `12.) Garage layout of the parking garage` 

# `Actor: Parking Operator` 

```
Purpose: Creating a layout of the parking garage for the drivers to view.
```

```
Steps:
```

- `The operator creates a layout of the parking garage.` 

- `The parking operator creates the levels, lanes, and parking spaces.` 

- `The parking operator then links an overhead sensor to track the parking` 

- `spots.` 

- `13.) Parking expiration time & session extension` 

```
Actor: Driver
```

```
Purpose: When the parking expiration is about to expire, the driver extends the
reservation time.
```

```
Steps:
```

```
-
The system will notify the driver that their parking time is about to
expire.
```

- `The driver has the decision to choose if he/she wants to add more time to` 

- `the reservation.` 

- 

- `The driver would then need to pay a small fee for extra time.` 

# `14.) Automated exit and digital receipts` 

```
Actor: Driver and System
```

```
Purpose: The system ends the parking session by giving the driver a receipt and
opening the gate.
```

```
Steps:
```

- `Once the driver leaves he parking the spot the overhead sensor will turn` 

```
red
```

- `The system has updated and has kept the spot available.` 

- `The system will give the driver a receipt and open the exit gate for them.` 

# `15.) Filtered reservation for eclectic vehicle` 

# `Actor: Driver that owns an electric car` 

```
Purpose: Has a filtered layout for where the charging stalls are and allows the
drivers to reserve it.
```

# `Steps:` 

- `The driver goes to the app and clicks on the â€œEV Chargingâ€ filter tab. �` 

- `The app will then show the drivers where the EV charging stalls are` 

- `located in the parking garage.` 

- `The driver reserved an EV spot.` 

