# AutoDB.AI

AutoDB.AI is an AI-powered tool that simplifies database creation by automating schema generation, SQL coding, and ER modeling. It streamlines database management, reducing manual effort and enhancing efficiency.

##  Problem Statement
Manually designing and managing databases is time-consuming and error-prone. Developers often struggle with schema creation, normalization, and query optimization, leading to inefficiencies.

##  Our Solution
AutoDB.AI leverages AI to automate:
- Schema generation based on user requirements.
- Real-time ER diagram updates.
- SQL script generation for easy database deployment.
- Seamless synchronization and data export options.

##  Key Features
- **AI-Powered Schema Generation** – Automatically suggests optimal database schemas.
- **Real-Time ER Diagram Updates** – Visual representation of the database structure.
- **Seamless Synchronization** – Syncs schema changes across various formats.
- **Export Options** – SQL, JSON, CSV, PDF formats available.
- **User-Friendly Interface** – Intuitive UI for database creation.
- **User Authentication** - Secure login and signup using Firebase.

##  How It Works
1. **Input Requirements** – User provides entity details.
2. **AI Processing** – Algorithm generates optimized schema.
3. **ER Diagram & SQL Code Generation** – Real-time visualization and SQL script output.
4. **Export & Deployment** – User can export schema in various formats.

##  Technologies Used
- **Backend**: Node.js, Express.js
- **Frontend**:  React (Vite), TailwindCSS
- **Database**: Firestore
- **Authentication**: Firebase auth


## 📂 Project Structure

```
├── client/               # Frontend code
├── server/               # Backend API
├── shared/               # Shared utilities
├── auth/                 # Authentication-related pages
├── pages/                # Main application pages
├── components/           # Reusable UI components
├── .env                  # Environment variables
├── README.md             # Project documentation
├── package.json          # Dependencies
```

## 🔧 Setup Instructions

1. **Clone the repository**

   ```sh
   git clone https://github.com/YOUR_USERNAME/AutoDB.AI.git
   cd AutoDB.AI
   ```

2. **Install dependencies**

   ```sh
   npm install
   ```

3. **Set up Firebase**

   - Create a Firebase project
   - Enable Firestore and Authentication
   - Add Firebase config to `.env` file

4. **Run the application**

   ```sh
   npm run dev
   ```

## 🔮 Future Enhancements
- **NoSQL Database Support** – Expanding to MongoDB.
- **AI-driven Query Optimization** – Automating SQL query improvements.
- **Database Migration Features** – Enabling seamless migration between database types.

## 🤝 Contributing
We welcome contributions! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request (PR) on GitHub.

## 📜 License

This project is licensed under the MIT License.
- - -