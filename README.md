# nest-health

This NestJS module adds a `/health` endpoint to your project.

## Installation

```typescript
import { HealthModule } from "@chqrd/nest-health";
import { Module } from "@nestjs/common";

@Module({
  imports: [HealthModule],
})
export class AppModule {}
```

### Project setup

```bash
$ npm install
```

### Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
