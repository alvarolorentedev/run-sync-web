# run-sync-web

# Dominio comprado run-sync.com

# Objetivo

Crear un servicio que sincronice todas las apps de running.
El usuario debera loguearse en nuestro sistema.
El usuario podra loguearse a todas las Apps y podra ver un listado de sus carreras por APP
En cada tarjeta con la informacion podriamos mostrar si lo tiene sincronizado con otras (nos basaremos o en ID o en la fecha/hora)

# Necesitamos
Front end web (me gusta este template: http://rubix410.sketchpixy.com/)
    * Login page / Sign up
    * Profile page
    * Linking page (enlazar con las distintas apps para obtener los datos de ahi)
    * activity list
        - Sort by date / app
    * Activity
        - Exportar a... (otra app o csv)
        - Ver detalles
Database
    Mongo Database
Server
    Donde la magia ocurre

# Idea
Cada app tiene un modelo de datos distinto, por lo que habria que crear un modelo unico para todos. 
Debemos crear un conversor de Datos X (Nike, Endomondo, Runtastic, ...) a nuestro modelo y de nuestro modelo a X (Nike, Endomondo, Runtastic, ...)

# Free / Free + Premium / Premium
Podemos pensar en hacerla gratis pero solo haciendo el intercambio entre 2 cuentas (por ejemplo)
Cobrar por que el sistema a diario por la noche automaticamente haga la sincronizacion
Cobrar por hacer intercambio de datos entre mas cuentas
Exportar datos