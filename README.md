# Kinship — Social Wellness Support System

A responsive front-end project prototype for a social wellness support website. Includes a demo login screen, wellness dashboard, simulated sensor readings, guided breathing, grounding activity, beginner-friendly yoga/movement instructions, mood check-in and local trusted-contact list.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a modern browser. No build tools are required.
3. Use any name and a password of at least four characters to enter demo mode.

## Important project limitations
- The login is **front-end demo access only**. It does not securely authenticate users. For a real business deployment, use a backend authentication service, password hashing, HTTPS, secure sessions, rate limiting, and appropriate account recovery.
- Sensor readings are simulated random/sample values. No physical sensor, wearable or medical device is connected.
- Contacts are held only in the current browser session and are not sent messages or emergency alerts.
- Mood notes and wellness data are not uploaded to a server. Do not enter sensitive or real medical information in this demo.
- Wellness content is general information and not medical advice or diagnosis.

## Suggested next steps for a production website
1. Choose a domain and hosting provider; configure HTTPS.
2. Build a backend API and database with user consent and access controls.
3. Integrate a supported sensor/wearable using its documented SDK/API and validate the data.
4. Add secure authentication, data retention/deletion controls, privacy policy and consent flows.
5. Add real notification and emergency workflows only after validating reliability, permissions and local legal requirements.

## Suggested diagrams for project review
Use SPARX Enterprise Architect to create a Data Flow Diagram and four UML diagrams based on the implementation:
- Use Case Diagram: User, trusted contact, administrator; login, view dashboard, monitor readings, breathing/yoga, mood check-in, manage contacts.
- Activity Diagram: Sign-in → dashboard → choose wellness feature → interact → save local check-in / return.
- Sequence Diagram: User → website UI → authentication service (future backend) → dashboard; clearly label backend as proposed, not implemented.
- Class Diagram: User, SensorReading, WellnessSession, MoodCheckIn, TrustedContact, WellnessDashboard.

For the report and viva, distinguish what is implemented in this front-end prototype from what is planned for a future full-stack release.
