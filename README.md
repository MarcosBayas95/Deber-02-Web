# Deber de Desarrollo de aplicaciones Web
## Instrucciones:

Para la parte 5 del desarrollo del deber se decidio utilizar el framwork de [Tailwind CSS](https://tailwindcss.com/docs/installation) el cual nos provee de muchas clases ya configuradas para utilizarlas en algun proyecto.

Debido a que hay varias maneras de utilizar Tailwind, se opto por utilizar su CLI que es como se acostumbra a trabajar con el framwork, ya que este provee de mas funcionalidades que el CDN.

* Para realizar un menu de hamburguesa para pantallas mas pequeñas, se utilizo javascript para generar los eventos del click, y webpack para generar el script de produccion (bundle.js).

    Antes de utilizar tailwind debera instalar los modulos de node con el siguiente comando en el terminal:
    ```
    npm install
    ```

<br/>

* Si se desea utilizar Tailwind para añadir mas funcionalidades en modo de desarrollo debera ejecutar en el terminal:

    ```
    npm run dev
    ```
    Este comando iniciara un modo observable y actualizara la hoja de estilos asociada al archivo html segun usted añada clases.

<br/>

* Para ejecutar el build de produccion, en el terminal debera usar:
    ```
    npm run build
    ```
    Este comando minificara el css generado con tailwind haciendolo mas liviano y listo para produccion.

