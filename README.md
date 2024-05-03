# Plant Tracker App (Working Title)

This site will allow users to sign in with Google or create an account manually, enter their zip code, see upcoming weather data in their dashboard along with watering and fertilization schedules, and maybe recommend other plants with similar care instructions. In a separate form, users will be able to add their plants, a photo of their plants, care instructions, or use a 'Prefill with AI' button to let a custom OpenAI agent fill all care instructions fields for them (hopefully based on zip). Users will also be able to view details about each plant, make any edits regarding care instructions and add any notes or mark the plant as watered and/or fertilized. Waterings and fertilizations will populate a log event that will also be stored on each plant's detail page as well as a section in the dashboard showing the previous 5 or so logs in addition to populating a dedicated log page. There will also be a schedule page that will show which plants will need waterings in the current month.

I do not plan to implement a desktop compatible version of this application. The ultimate goal, to which I've done zero research into, is to develop this to be an Android app and avoiding deployment to a domain that people can visit if I can help it. I've heard Kotlin is used commonly for Android apps. I don't have any plans to pay for Apple's developer license to release an iOS build with Swift as it seems pretty steep for the passion project of a (currently) unemployed developer.

[Take a look at the wireframe here.](https://www.figma.com/file/Z2fpMUHFPUmYA94A2G6FqP/Plant-Tracker-App?type=design&node-id=0%3A1&mode=design&t=UyYgAtxL0NLSfF9k-1) [View the ERD here.](https://dbdiagram.io/d/plant-tracker-app-663513885b24a634d0744bbd)

## Features

- Track and manage plant care right in the app by creating, updating, and (hopefully not) deleting plants
- Retroactively log care events if the app isn't used on date of watering/fertilization
- Weather API via [OpenWeather](https://openweathermap.org/api)
- Care assistance from AI via [OpenAI's API](https://openai.com/api)
- Image hosting via [Cloudinary](https://cloudinary.com/documentation/image_upload_api_reference)
- Sign in with Google or create an account manually
- Finally if all goes according to plan, a mobile app for Android

## Getting Started
These instructions will get you a copy of the project's front-end up and running on your local machine for development and testing purposes. You will also need to clone and follow the installation and setup instructions for the back-end (coming soon!).

### Prerequisites
Ensure you have the latest version of Node.js and npm installed and are running the project on a Windows/Mac/Linux machine.

### Installation and Setup
1. Clone this repository:
```
git clone git clone git@github.com:macleann/plant-tracker-client.git
```

2. Navigate to the project directory:
```
cd plant-tracker-client
```

3. Install dependencies:
```
npm install
```

4. Start the application in development mode:
```
npm start
```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000)

## Tech Stack
- React's TypeScript template
- Tailwind CSS
- Material UI
- Google Sign-in

## Contact
Neil MacLean - [nbmac13@gmail.com](mailto:nbmac13@gmail.com)