# Mission Prerna

Mission Prerna is a set of initiatives under the government of Uttar Pradesh to enable smoother
functioning of education delivery in the state. Under the mission we are focusing
on [Nipun Bharat](https://nipunbharat.education.gov.in/)
initiatives to ensure every student in the state is Nipun (competent).

## Technical Elements

* Nipun Lakshya Android Application
* Nipun Lakshya Backend Services

### Nipun Lakshya Android application

The [Nipun Lakshya Android Application](https://play.google.com/store/apps/details?id=org.samagra.missionPrerna&hl=en_IN&gl=US)
is used by parents, teachers, examiners and mentors. With the app parents & teachers can help
students prepare for assessments. Mentors can perform assessments using the app.

The application is predominantly written in Java with newer elements in Kotlin. The app extensively
uses a modified version of ODK to collect data. The app uses Hasura for easier access and storage of
some of our data elements. The app talks to our backend service for authentication and access
control.

Repository: https://github.com/Mission-Prerna/Nipun-Lakshya-App

### Nipun Lakshya Backend Services

The backend services for Nipun Lakshya provide support to the above Android applications in user
management, authentication & access control via SamagraX's
opensource [user-service](https://github.com/Samagra-Development/user-service).

Repository: https://github.com/Mission-Prerna/PrernaLakshyaBackend

To easily deploy the backend system locally kindly refer: https://github.com/Mission-Prerna/sandbox-deployment
