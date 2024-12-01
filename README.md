# docs

- бизнес флоу - https://excalidraw.com/#json=AbD0-Tjzdo_J8Yt2R_L1r,OnDc05Uq-nfJnjilMpyvBQ

## запуск

- необходимо иметь на машине docker и git

- git clone https://github.com/dung30n-cod3rs/EmployeeMotivationSystemBackend.git hacathon-backend && cd hacathon-backend
- docker compose up --build -d

- git clone https://github.com/dung30n-cod3rs/frontend.git hacathon-frontend && cd hacathon-frontend
- docker build -t frontend . && docker run -p 3000:3000 frontend

если не билдит фронт

- npm install -g bun (или любым другим способом установить bun - https://bun.sh/docs/installation)
- git clone https://github.com/dung30n-cod3rs/frontend.git hacathon-frontend && cd hacathon-frontend
- bun install
- bun run dev
