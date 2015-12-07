package Trivial;

import Keyboard.*;

public class Trivial{

	public static void main (String[]args){
		
		String preguntes[];
		String RespostaCorrecta[];
		String RespostaIncorrecta1[];
		String RespostaIncorrecta2[];

		preguntes = new String[20];
		RespostaCorrecta = new String[20];
		RespostaIncorrecta1 = new String[20];
		RespostaIncorrecta2 = new String[20];
		System.out.println("Jugem!!!!!!");
		System.out.println("***********");
		

	}
	private static String omplena (String[]preguntes, String[]RespostaCorrecta, String[]RespostaIncorrecta1, String[]RespostaIncorrecta2){
		
		preguntes[0]= "Si nos vemos obligados a frenar durante el trazado de una curva, debemos utilizar...";
		preguntes[1]= "Si circula conduciendo su motocicleta por una travesía con dos carriles para cada sentido y que carece de arcenes, debe saber que no le está permitido rebasar la velocidad máxima de...";
		preguntes[2]= "Su motocicleta está equipada con frenos de tambor. ¿Qué mantenimiento precisa dicho sistema de frenos?";
		preguntes[3]= "En relación con el casco de protección, el motorista debe saber que...";
		preguntes[4]= "Si circula con su motocicleta por una vía urbana de doble sentido y desea estacionar, ¿en qué lado debe hacerlo?";
		preguntes[5]= "Ante un accidente de tráfico, ¿cuál es la primera medida a adoptar?";
		preguntes[6]= "La motocicleta que se observa en la fotografía tiene sus neumáticos en perfecto estado y circula por una calzada seca y con pavimento en buen estado. En caso de frenada, las anteriores condiciones...";
		preguntes[7]= "La fatiga, el alcohol o el mal tiempo, ¿influyen en los accidentes?";
		preguntes[8]= "Circulando con su motocicleta, ¿cómo actuará a la vista de la señal que se observa en la fotografía?";
		preguntes[9]= "Cuando los motoristas circulan en grupos grandes...";
		preguntes[10]= "Una motocicleta de más de cuatro años de antigüedad, ¿cuándo debe pasar la inspección técnica reglamentaria?";
		preguntes[11]= "Un permiso de conducción caducado...";
		preguntes[12]= "La disposición más generalizada de los mandos en la motocicleta es la que permite accionar con la mano izquierda...";
		preguntes[13]= "Al realizar con su motocicleta un giro muy cerrado a una velocidad de 30 km/h, ¿qué puede suceder si al describir dicho giro aprieta fuertemente el freno delantero?";
		preguntes[14]= "Con su motocicleta, ¿cuál debe ser su comportamiento ante un semáforo amarillo fijo?";
		preguntes[15]= "¿Es correcto situar toda la carga en la parte trasera del vehículo?";
		preguntes[16]= "Si conduce una motocicleta que tiene un motor de explosión de cuatro tiempos, ¿con qué tipo de mezcla funciona este motor?";
		preguntes[17]= "Generalmente, ¿cuándo comienzan a manifestarse los efectos del alcohol en la conducción?";
		preguntes[18]= "De acuerdo con las circunstancias que se observan en la imagen, ¿circula correctamente el motorista?";
		preguntes[19]= "Circula conduciendo su motocicleta y utiliza el espejo retrovisor para comprobar si puede efectuar un cambio de carril. ¿Es correcto este comportamiento?";
		
		RespostaCorrecta[0]= "simultáneamente los dos frenos, el delantero con menor presión y aumentarla con el trasero.";
		RespostaCorrecta[1]= "50 km/h.";
		RespostaCorrecta[2]= "Sustituir las zapatas si se encuentran desgastadas y limpiarlas si fuera necesario.";
		RespostaCorrecta[3]= "debe estar homologado.";
		RespostaCorrecta[4]= "En el lado derecho.";
		RespostaCorrecta[5]= "Señalizar y proteger la zona.";
		RespostaCorrecta[6]= "favorecerán el que no aumente la distancia de detención.";
		RespostaCorrecta[7]= "Sí, son factores de riesgo que aumentan la probabilidad y gravedad de los accidentes.";
		RespostaCorrecta[8]= "Manteniendo encendida, al menos, la luz de corto alcance o de cruce.";
		RespostaCorrecta[9]= "no deben ir todos juntos, sino divididos en subgrupos distanciados entre sí.";
		RespostaCorrecta[10]= "Cada dos años.";
		RespostaCorrecta[11]= "no autoriza a conducir a su titular.";
		RespostaCorrecta[12]= "la maneta de embrague, la bocina y las luces.";
		RespostaCorrecta[13]= "Que la rueda delantera quede bloqueada y produzca una caída.";
		RespostaCorrecta[14]= "Detenerme como si se tratara de una luz roja, si es posible hacerlo con seguridad.";
		RespostaCorrecta[15]= "No, porque al aumentar el peso en la rueda trasera, la motocicleta puede bascular durante la marcha.";
		RespostaCorrecta[16]= "Con gasolina y aire.";
		RespostaCorrecta[17]= "Inmediatamente y sus efectos alcanzan el punto máximo una hora después de haber bebido la última copa.";
		RespostaCorrecta[18]= "No, porque no está permitido circular sobre las marcas discontinuas que separan los carriles.";
		RespostaCorrecta[19]= "Sí, y en caso de duda es aconsejable además girar ligeramente la cabeza para comprobar si se puede realizar la maniobra.";
		
		RespostaIncorrecta1[0]= "solamente el freno delantero.";
		RespostaIncorrecta1[1]= "90 km/h, porque no tiene arcén.";
		RespostaIncorrecta1[2]= "Sustitución de las pastillas si se encuentran desgastadas.";
		RespostaIncorrecta1[3]= "debe quedar bastante holgado para que cumpla su función protectora.";
		RespostaIncorrecta1[4]= "En el lado izquierdo.";
		RespostaIncorrecta1[5]= "Identificar a los heridos inconscientes.";
		RespostaIncorrecta1[6]= "favorecerán el que disminuya la distancia de reacción.";
		RespostaIncorrecta1[7]= "No, porque los factores de riesgo son otros.";
		RespostaIncorrecta1[8]= "Apagando el alumbrado de corto alcance, en cumplimiento de la señal.";
		RespostaIncorrecta1[9]= "pueden ir todos juntos y ocupar toda la calzada.";
		RespostaIncorrecta1[10]= "Cada año.";
		RespostaIncorrecta1[11]= "no podrá ser prorrogado.";
		RespostaIncorrecta1[12]= "el puño acelerador y la maneta del freno delantero.";
		RespostaIncorrecta1[13]= "Nada, debido a que a esta velocidad el efecto giroscópico estabilizaría la motocicleta.";
		RespostaIncorrecta1[14]= "Acelerar para pasar antes de que cambie a luz roja";
		RespostaIncorrecta1[15]= "Sí, es el lugar más apropiado para la carga más pesada.";
		RespostaIncorrecta1[16]= "Con gasóleo, aceite y aire.";
		RespostaIncorrecta1[17]= "A la hora de haber tomado última copa.";
		RespostaIncorrecta1[18]= "Sí, porque al estar la vía saturada no interrumpe la circulación de los turismos.";
		RespostaIncorrecta1[19]= "Sí, si después de realizar la maniobra la señalizo.";
		
		RespostaIncorrecta2[0]= "solamente el freno trasero.";
		RespostaIncorrecta2[1]= "100 km/h, porque es una vía interurbana.";
		RespostaIncorrecta2[2]= "Comprobación de la viscosidad del líquido de frenos y su relleno, si fuera preciso, con aceite multigrado.";
		RespostaIncorrecta2[3]= "es preferible utilizar el tipo";
		RespostaIncorrecta2[4]= "En el lado derecho o en el izquierdo indistintamente.";
		RespostaIncorrecta2[5]= "Taponar las hemorragias de los heridos.";
		RespostaIncorrecta2[6]= "provocarán un aumento en la distancia de frenado.";
		RespostaIncorrecta2[7]= "No, ya que un accidente es impredecible.";
		RespostaIncorrecta2[8]= "Apagando la luz de corto alcance o la sustituyéndola por la de largo alcance o de carretera.";
		RespostaIncorrecta2[9]= "deben circular muy juntos, para que puedan ser adelantados con facilidad por otros vehículos.";
		RespostaIncorrecta2[10]= "Cada seis meses";
		RespostaIncorrecta2[11]= "sólo podrá prorrogarse si su titular supera de nuevo las pruebas prácticas y teóricas correspondientes.";
		RespostaIncorrecta2[12]= "la maneta de embrague y se acciona el puño acelerador.";
		RespostaIncorrecta2[13]= "Que la rueda trasera quede bloqueada por la fuerza cinética y se produzca una caída.";
		RespostaIncorrecta2[14]= "Pasar igual que si fuera intermitente.";
		RespostaIncorrecta2[15]= "Sí, es el lugar más idóneo para situar cualquier tipo de carga.";
		RespostaIncorrecta2[16]= "Con gasolina, aceite y aire.";
		RespostaIncorrecta2[17]= "Inmediatamente y sus efectos desaparecen totalmente a la hora de haber bebido la última copa.";
		RespostaIncorrecta2[18]= "Sí, porque así puede adelantar con más facilidad.";
		RespostaIncorrecta2[19]= "Sí, pero solamente si voy a realizar un cambio de carril hacia la derecha.";
		
		return (preguntes[19]);
	}
	private static int mostra (String[]preguntes, String[]RespostaCorrecta, String[]RespostaIncorrecta1, String[]RespostaIncorrecta2, int quina){
	 
		quina = (int)Math.floor(Math.random()*20);
		
		System.out.println(preguntes[quina]);
		
		return quina;
		
		
		//String a = omplena(preguntes[quina], RespostaCorrecta[quina], RespostaIncorrecta1[quina], RespostaIncorrecta2[quina]);

		//System.out.println(a);
	
		
	}
	private static boolean repetida(int[]sortides, int quantes, int quina){
		
	}
	private static int afegir (int[]sortides, int quantes, int quina){
		
	}
	private static void totesCorrectes (String[]preguntes, String[]RespostaCorrecta){
		
	}

}
