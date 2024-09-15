# Website Manager Panel

## Tính năng
- Manager : 
    + 

### Công nghệ
- FE: [NextJs v14]
- BE: [ExpressJs v10]
- DB: [MongoDB]

- local app: http://localhost:3000
- local api: http://localhost:5001

Tài khoản admin
Username: admin1
Password: admin1


### Các scripts

```sh
"scripts": {
    "start": "concurrently \"cd backend && npm run start\" \"cd frontend && npm run start\"",
    "dev": "concurrently \"cd backend && npm run dev\" \"cd frontend && npm run start\"",
    "install-all": "concurrently \"cd backend && npm install\" \"cd frontend && npm install\"",
    "format": "concurrently \"cd backend && npm run format\" \"cd frontend && npm run format\""
},
// Khởi chạy cả backend và client
npm run start
//  Khởi chạy cả backend (developer) và client
npm run dev
// cài package cho backend và client
npm run install-all
// format code cho backend và client
npm run format
```