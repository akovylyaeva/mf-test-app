## Module Federation test app

**These folders contain two different services!!**

To start each service, you must install modules if it needs
```
npm ci
```

And then enter the command
```
npm run dev
```

You can test it 

1. Open the consumer-service using the link http://localhost:2000/ 
2. Change the text of the button in the provider-service
3. You see that it automatically changes in the consumer-service

The following guide was used for setting up:
https://module-federation.io/guide/start/quick-start.html