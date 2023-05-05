
# TO DO:
1. Video seguido https://www.youtube.com/watch?v=05rP763gCuo&list=PL_WGMLcL4jzXtyaAfqln4IFePvdNmionM&index=1&ab_channel=LeiferMendez
2. En front hacer pull de rama pushNotifTest, npm i http-server -g
3. Para probar en local solo es con HTTPS, hacer build --prod sin ninguna bandera extra, cd /dist/front http-server http://localhost:8080/#/demo
4. npm i web-push
5. El body recibido en /api/getnotif (endpoint prueba), es el pushSubscription que usa webpush.sendNotification para enviar notif al navegador
6. Enviar ese body a la funcion enviarNotificacion para usarlo en el método webpush.sendNotification
7. enviarNotificacion debería llamarse cuando hayan nuevos pedidos.