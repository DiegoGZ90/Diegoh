package CalculadoraEspecial;


public class Calculadora {    

    static void calcularAreaTriangulo(int i) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    static String CalcularAreadelRectangulo(int i) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
    //Atributos de Clase, pueden ser Publicos, Privados y Protegidos (en herencia)
    public String tipoCalculadora;
    public String color;
    public int dimensionPantalla;
    private String numeroDeSerie;
    private String nombrePropietario;
    
    //Constructor de la calse
    public Calculadora(String propietario){
        this.tipoCalculadora="Calculadora Básica";
        this.dimensionPantalla=10;
        this.numeroDeSerie="12345abc";
        this.color="Azul";
        this.nombrePropietario=propietario;
    }
    
    //Constructor vacio
    public Calculadora(){
    }
    
    //Are de declaración de metodos
    //en clase hemos dicho "funciones" anteriormente, pero en POO son metodos.
    public double sumar(double primerNumero, double segundoNumero){
        return primerNumero + segundoNumero;
    }
    
    public double restar(double primerNumero, double segundoNumero){
        return primerNumero - segundoNumero;
    }
    
    public double multiplicar(double primerNumero, double segundoNumero){
        return primerNumero * segundoNumero;
    }
    
    public double dividir(double primerNumero, double segundoNumero){
        return primerNumero / segundoNumero;
    }
    
    public double raizCuadrada(double numero){
        return Math.sqrt(numero);
    }
    public double calcularInteresSimple(double capital, double tasa, double tiempo) {
        return capital * tasa * tiempo;
        
    }
     public double calcularAreaTriangulo(double base, double altura) {
        return (base * altura) / 2;
        
    }
     public double calcularAreaCirculo(double radio) {
    return Math.PI * Math.pow(radio, 2);
    }
     public double calcularPerimetroCirculo(double radio) {
    return 2 * Math.PI * radio;
    }
      public double calcularAreaRectangulo(double base, double altura) {
        return base * altura;
        }

     public boolean esPositivo(int numero) {
    return numero > 0;
    }

    public boolean esPrimo(int numeroBuscado){
        boolean primo = false;
        int contador = 0;
        for(int i = numeroBuscado; i > 0; i--){
            if(numeroBuscado % i == 0 ){
                contador++;
            }
        }
        return contador == 2;
    }   

    void calcularInteressimple(int i) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    String calcularInteresSimple(int i) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
}

