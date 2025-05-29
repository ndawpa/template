# NextJS Init
```
rm .gitkeep && npx create-next-app@latest . --ts --tailwind --eslint --app --src-dir --import-alias "@/*"
```

```
npm run dev
```

# NestJS Init
```
npx @nestjs/cli new . --package-manager npm --language TypeScript --strict
```
```
npm run start:dev
```

# React Native Expo

```
npx create-expo-app . --template expo-template-blank-typescript
```
```
npx expo start
```
or
```
npx expo start --tunnel
```

# Docker
```
docker build . -t web
```
```
docker build . -t api
```

# Docker Compose
It's not working as expected. Fix later.

```
docker compose build --no-cache
docker-compose up -d --build
```