# ProyectoFuente
Segundo proyecto de Mantenimiento Electrónico. Fuente de alimentacion.

PROPUESTA:

Una empresa líder en la industria de telefonía móvil, nos ha contratado para desarrollar una fuente
de alimentación lineal personalizada. Este proyecto implica la aplicación de conocimientos
avanzados en ingeniería electrónica y eléctrica para diseñar una fuente de alimentación eficiente,
estable y confiable que cumpla con los estándares de la industria móvil.

Condiciones que debe cumplir la instalación:
La fuente de alimentación deberá ser diseñada para transformar la energía eléctrica alterna de la
red (230 Vca y 50 Hz) en una salida de voltaje estable de energía eléctrica continua capaz de cargar
un teléfono móvil, es decir, 5 Vcc.
Se deberá tener en cuenta que la salida de corriente continua debe ser estable y sin rizado,
manteniendo en todo momento la tensión de salida requerida, solo de esta manera se pasarán
todos los estándares para su comercialización.

COMPONENTES NECESARIOS:

Transformador: CROVISA 230Vac/15Vac o 12Vac, 12VA, 80mA.

Rectificador: DB10M, 1000 Vr, Iout 1A.

Fitro: B41888C5338M000, 3300 uF, 25 Vdc.

Regulador: L7805CV, 35Vdc input, 5Vdc output.

Disipador: SK129/38.1STS, Rth 6,5 k/w.

C1 para regulador: MKS0C033300D00MSSD, 0.33 uF, 63 Vdc.

C2 para regulador: K471J15C0GF5TH5, 470 pF, 50 Vdc.

Conectores x2 E/S: 282836-2

Puerto USB: 292303-3

FUNCIONAMIENTO DEL SISTEMA:

El sistema consiste en una fuente de alimentación lineal la cual transforma una corriente alterna de 230V en 5V de corriente continua. La fuente está compuesta por un transformador que convierte esos 230V AC en 15V AC mediante inducción electromagnética. Al generar tensión en el devanado primario se origina un flujo magnético en el núcleo de hierro. Este flujo viajará desde el devanado primario hasta el secundario. Después pasa por el rectificador el cual  es un puente de diodos que rectifica la señal haciendo que el voltaje siempre esté en el lado positivo, es decir, elimina la parte negativa de la señal. Luego pasa por el filtro que es un condensador polarizado que suaviza la señal haciendo ondas mucho menos pronunciadas. Y por último pasa por el regulador que está unido a un disipador de calor porque en el proceso el regulador alcanza temperaturas muy altas, el cual termina el proceso disminuyendo el valor de rizado y fijando una tensión de salida constante.

SIMULACION Y MEDICIONES CON EL OSCILOSCOPIO EN PROTEUS:

<img width="461" alt="Esquema Proteus" src="https://github.com/user-attachments/assets/a4f05d23-83c1-4d28-9ab4-5b423d98d5ae">

<img width="384" alt="Mediciones con osciloscopio (Transformador)" src="https://github.com/user-attachments/assets/7c1d5238-9ecf-4bf6-aa17-d70af8d65b1c">

<img width="371" alt="Mediciones con osciloscopio (Rectificador)" src="https://github.com/user-attachments/assets/c076c506-7057-4307-bb8f-9c24454828d7">

<img width="371" alt="Mediciones con osciloscopio (Regulador)" src="https://github.com/user-attachments/assets/63513003-c23a-45f1-8718-874f12c02f35">

CALCULOS PARA LOS COMPONENTES:

<img width="248" alt="Captura" src="https://github.com/user-attachments/assets/a9504332-f29d-47fa-9c80-c44cce03d964">

ESQUEMA REALIZADO EN ALTIUM:

<img width="462" alt="Captura" src="https://github.com/user-attachments/assets/6c67324a-bc6f-4f91-b8af-568d7b4754fc">

SIMULACION CON LA PROTOBOARD:

<img width="271" alt="Simulacion con protoboard" src="https://github.com/user-attachments/assets/69fe1cfd-de78-45be-b844-b577a10b9109">

En la protoboard hemos montado nuestra fuente de alimentación lineal para comprobar si la tensión de salida nos da 5 Vcc, también se colocó un led de encendido para poder saber si la fuente de alimentación estuviera conectado correctamente.

<img width="243" alt="S2" src="https://github.com/user-attachments/assets/7878a991-1690-4481-8fa1-05b4845cd5f7">

Como se puede observar la tensión de salida de nuestra fuente de alimentación lineal es 4,98 Vcc que equivale a 5 Vcc.

DISEÑO PCB EN ALTIUM

<img width="314" alt="PCB en Altium" src="https://github.com/user-attachments/assets/31535150-ca5e-4f3d-9b28-6f1f51f23dda">

<img width="314" alt="PCB en Altium 3D" src="https://github.com/user-attachments/assets/9886edf0-bbcd-4d1c-8188-68a4708d71d8">

<img width="286" alt="PCB en Altium Routes and Pads" src="https://github.com/user-attachments/assets/7dd7f46e-101a-4a22-9cea-c2786ccc905f">

NOTA: 

1.Aumentar el Ancho de pistas -> 1,5mm.

2. Tamaño de los Pads (recordar que los pads son la región metálica expuesta de la placa de circuito impreso donde se  suelda) -> 2,54mm. (Así es más fácil luego para soldar.)

3. Trata de hacer  las pistas en el Bottom Layer.

MONTAJE FINAL:

<img width="315" alt="Montaje Final" src="https://github.com/user-attachments/assets/48607dce-679f-481f-b376-d374ce75513f">

<img width="226" alt="Montaje Final 2" src="https://github.com/user-attachments/assets/51703dfc-7aec-4aa2-a504-35be4ebf00c7">

VIDEO FINAL:

https://drive.google.com/drive/folders/1kIc3slkXnFMzkk8PTJN3GtMxK4tg7k69?usp=drive_link

