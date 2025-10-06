# BookShoppingCartMvc (A basic e-comm system for beginners)📚🛒

It is a source code of the youtube tutorial on [book shopping cart in .net core mvc](https://www.youtube.com/watch?v=R4ZLWD89R5w&list=PLP8UhDwXI7f_8r2Rbt7GNwf7eXZqUu_p4). Initially it was designed to explain how shopping cart 🛒 works in dot net core mvc. But now it has more features except payment gateway. A ⭐ in repository is highly appreciated, helps to promote my content.

📢 Initially , this project was built with .net 7. But it is **Upgraded to .net 9.0.** now and I will try to keep it up to date.

## Tech stack 🧑‍💻

   - Dotnet core mvc (.Net 9)
   - MS SQLServer 2022 (Database)
   - Entity Framework Core (ORM)
   - Identity Core (Authentication)
   - Bootstrap 5 (frontend)

## Tools I have used and their alternative

- Visual Studio 2022 (Alternatives (.NET SDK + VS Code or .NET SDK + JetBrains Rider)
- Microsoft Sql Server Management Studio (Alternative Azure data studio or you can just execute sql from terminal)

Note: Every tool and tech is free for personal use. 

## Video tutorial 📺

[Youtube playlist](https://www.youtube.com/watch?v=R4ZLWD89R5w&list=PLP8UhDwXI7f_8r2Rbt7GNwf7eXZqUu_p4)

## How to run the project?🌐

1. Open the command prompt. Go to a directory where you want to clone this project. Use this command to clone the project.

```bash
git clone https://github.com/rd003/BookShoppingCart-Mvc
```

2. Go to the directory where you have cloned this project, open the directory `BookShoppingCart-Mvc`. You will find a file with name `BookShoppingCartMvc.sln`. Double click on this file and this project will be opened in Visual Studio.

3. Open `appsettings.json` file and update connection string.

```json
"ConnectionStrings": {
  "conn": "data source=your_server_name;initial catalog=MovieStoreMvc; integrated security=true;encrypt=false"
}
```

4. Run the project.

📢 When you run the project for the first time, it will do following things:

- It will generate the database
- It will seed some data
- It will create an account for `admin`

## How to logged-in with admin account?? 🧑‍💻🧑‍💻

Click on the link named `login` and get logged-in with these credentials.

```text
username: admin@gmail.com

password: Admin@123
```

