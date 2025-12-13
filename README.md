🗂 Project Structure
      IT Asset Tracking Portal (ITAMS)
├── src/
│   ├── main/
│   │   ├── java/com/example/itassettrackingportal/
│   │   │   ├── config/          # Security & Data initialization
│   │   │   ├── controller/      # Admin, Employee, Asset, Ticket, Feedback
│   │   │   ├── model/           # Entities & Enums
│   │   │   ├── repository/      # JPA Repositories
│   │   │   ├── service/         # Business logic
│   │   │   └── dto/             # Data Transfer Objects
│   │   ├── resources/
│   │   │   ├── static/          # Images, CSS, JS
│   │   │   ├── templates/       # Thymeleaf HTML templates
│   │   │   │   ├── admin/       # Admin dashboards & forms
│   │   │   │   ├── employee/    # Employee dashboards & forms
│   │   │   │   ├── fragments/   # Header, footer, sidebar
│   │   │   │   ├── tickets/     # Ticket views/forms
│   │   │   │   └── index.html, login.html, register.html
│   │   │   └── application.properties

