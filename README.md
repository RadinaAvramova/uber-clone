# Uber Clone
Welcome to the Uber Clone project! This project is a replica of the popular ride-sharing application Uber, designed to provide users with a similar experience in booking rides, tracking drivers, and completing trips. With the Uber Clone, users can conveniently request rides, view estimated arrival times, and pay for trips, just like on the original platform.

## Features
1. **Ride Booking:** Allows users to easily book rides by specifying pick-up and drop-off locations, selecting ride preferences, and confirming requests.

2. **Driver Matching:** Matches users with nearby drivers based on availability, location, and ride preferences, ensuring quick and efficient pick-up times.

3. **Ride Tracking:** Provides real-time tracking of ride progress, allowing users to monitor driver location, estimated arrival times, and route details.

4. **Payment Processing:** Facilitates secure payment processing for rides using various payment methods such as credit/debit cards, digital wallets, or cash.

5. **Rating and Reviews:** Allows users to rate drivers and provide feedback on their ride experiences, helping maintain service quality and accountability.

6. **Trip History:** Maintains a history of past trips for users to review, including details such as date, time, route, fare, and driver information.


## App Setup

Clone the repository
```
git clone https://github.com/RadinaAvramova/uber-clone.git
```

Open a terminal, CD in to the folder and run these commands
```
npm i

cp .env.example .env
```

Now go to https://console.cloud.google.com/

Generate an API KEY.

You'll need to ENABLE Maps API, Directions API, Places API, and Distance Matrix API.

Add your new API KEY to the script inside **public/index.html**

![Screenshot 2022-11-23 at 17 40 53](https://user-images.githubusercontent.com/108229029/203526600-42f9f3be-6e9d-4fcc-aff0-5d6c6c7e8d87.png)

Now run this command to start the project 
```
npm run serve
```

And to start in PWA mode run the command
```
npm run pwa
```
![Screenshot 2022-11-23 at 17 44 01](https://user-images.githubusercontent.com/108229029/203527683-4b43f88e-07d8-4e2a-bfad-9a785afed02f.png)

Open another terminal
```

npm i

cp .env.example .env
```

Add the Google API Key to the .env

```
GOOGLE_MAPS_API_KEY=keyhere

npm run watch
```

![Screenshot 2022-11-23 at 17 53 00](https://user-images.githubusercontent.com/108229029/203529049-d7790bc7-0d0e-4b20-80d5-9cea46017c57.png)

You should be good to go!

## Usage
1. **User Registration:** Sign up for an account on the platform by providing your personal details and creating a password.

2. **User Authentication:** Log in to your account using your credentials or sign in with social media accounts if supported.

3. **Book a Ride:** Enter pick-up and drop-off locations, specify ride preferences (if any), and confirm your ride request.

4. **Track Ride Progress:** Monitor the progress of your ride in real-time, including driver location, estimated arrival time, and route details.

5. **Complete Payment:** Pay for your ride using the available payment methods, and receive a digital receipt for your records.

6. **Rate and Review:** Rate your ride experience and provide feedback on driver performance to help maintain service quality.

## Customization
You can customize the Uber Clone by modifying aspects such as the user interface design, ride preferences, payment methods, and additional features such as promotions or loyalty programs. Additionally, you can add new features, integrate with external services, or optimize performance for specific use cases.

# Application Images

<p float="left">
  <img width="270" alt="Screenshot 2022-11-23 at 17 10 03" src="https://user-images.githubusercontent.com/108229029/203521356-c0f3956f-2b71-4e53-998a-65d10ffd6f29.png">
  <img width="270" alt="Screenshot 2022-11-23 at 17 11 15" src="https://user-images.githubusercontent.com/108229029/203521447-f9ad69eb-67c1-4bc5-89c2-378d7a2dd27f.png">
  <img width="270" alt="Screenshot 2022-11-23 at 17 12 14" src="https://user-images.githubusercontent.com/108229029/203521544-3b982e89-ad62-4e63-a376-5f614acbb588.png">
</p>

![uberClone](https://github.com/RadinaAvramova/uber-clone/assets/99686592/e5d749ef-9ba1-4fae-83ec-11601150bbd6)

