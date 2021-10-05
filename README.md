/*(2.2.2.1) Crear un programa que pida números positivos al usuario, 
y vaya calculando la suma de todos ellos (terminará cuando se teclea un número negativo o cero). * /
usando el  sistema ;
 ejemplo de clase pública
{
     vacío estático  público Main ( )
    {
        int numero, resultado, resultado2 ;
 
        {
            Consola . WriteLine ( "tecle un numero positivo" ) ;
            numero = Convertir . ToInt32 ( Console . ReadLine ( ) ) ;
            resultado = numero ;
 
            Consola . WriteLine ( "teclee otro numero" ) ;
            numero = Convertir . ToInt32 ( Console . ReadLine ( ) ) ;
            resultado2 =  ( numero + resultado ) ;
            Consola . WriteLine ( "la suma es {0}" , resultado2 ) ;
            Consola . ReadLine ( ) ;
        }
        
        }
        
