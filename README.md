## Lab 5: Cupcake Order App (WAN ALISA SOFIA A220960)

This app guides users through a multi-screen process to select a cupcake quantity, flavor, and pickup date. The final details are displayed on a summary screen, which can be shared with other apps to send the order. To keep this data saved locally, the app uses **Room** with three core components:

* **Entity:** Defines the database table and its columns (like quantity, flavor, and date).
* **DAO (Data Access Object):** Handles database operations, using an `@Insert` function to save orders and a `@Query` function with `Flow` for real-time UI updates.
* **Database Class:** Acts as the main access point to connect the app with the database and provide the DAO.
