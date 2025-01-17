![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![Handlebars](https://img.shields.io/badge/Handlebars.js-f0772b?style=for-the-badge&logo=handlebarsdotjs&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# 👋🏼 'TIC TAC TOE'

'TIC TAC TOE' is a real-time web application built with Node.js and Socket.IO!

Players can create or join rooms where they can chat with each other. When a room has two players, a game of Tic Tac Toe can be started (if a room has more players, two players will be randomly selected).
![design landing page](https://github.com/ninadepina/tic-tac-toe/assets/89778503/33cf9b82-1179-47b0-bf8e-7a2d79e4a719)
![design room page](https://github.com/ninadepina/tic-tac-toe/assets/89778503/5e61beb8-61ff-434d-9196-0a7123e4cde8)

---

## 🛠️ Features

| Features                 | Status |
| :----------------------- | :----: |
| Choose username          |   ✅   |
| Create/join room         |   ✅   |
| Chat with other users    |   ✅   |
| Play Tic Tac Toe         |   ✅   |
| Switch between players   |   ✅   |
| Save game info on socket |   ✅   |
| Restart game             |   ✅   |
| Leave/delete room        |   ✅   |

---

## 👩🏼‍💻 How to use

1. Clone this repository

```
$ git clone https://github.com/ninadepina/tic-tac-toe.git
```

2. Install dependencies

```
$ cd tic-tac-toe
$ npm i
```

3. Create a .env file in the root of the project and add the following:

```
SESSION_SECRET=<YOUR SESSION SECRET>
PORT=<YOUR PORT>
```

4. Run the server

```
$ npm run start
// or when wanting to use nodemon
$ npm run start:dev
```

In your browser, go to `http://localhost:2222` (you can change the localhost PORT in the .env file)

---

## 📝 Documentation

Gain a better understanding and delve further into this project by reading the [process documentation](https://github.com/ninadepina/tic-tac-toe/blob/main/productdoc.md).

---

## 👁️ Demo

[rw-tictactoe.adaptable.app](https://rw-tictactoe.adaptable.app/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ninadepina/tic-tac-toe/blob/main/LICENSE) file for more details.
