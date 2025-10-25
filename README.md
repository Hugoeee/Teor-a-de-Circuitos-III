# Teoria-de-Circuitos-III
Apuntes sobre la asignatura de teoría de circuitos III en Ingeniería Eléctrica en la ETSIDI - UPM

1. Ecuación y Solución General (Primer Orden)
La ecuación diferencial que rige el circuito es: 
a 
1
​
  
dt
dD(t)
​
 +a 
0
​
 D(t)=g(t)
La solución total D(t) es la suma de la respuesta natural (D 
0
​
 (t)) y la respuesta en régimen permanente (D 
∞
​
 (t)): 
D(t)=D 
0
​
 (t)+D 
∞
​
 (t)
2. Componente Natural y Constante de Tiempo (τ)
La respuesta natural (D 
0
​
 (t)) se obtiene de la solución homogénea, y su límite es cero cuando t→∞: 
D 
0
​
 (t)=Ke 
− 
τ
t
​
 
 
La Constante de Tiempo (\tau) se define como: 
τ= 
a 
0
​
 
a 
1
​
 
​
 
3. Condiciones de Continuidad (D(0 
+
 ))
Para determinar la constante de integración K, necesitamos el valor de la función D(t) justo después del cambio (t=0 
+
 ). Este valor está íntimamente ligado al estado del circuito en t=0 
−
 . Para esto, aplicamos las condiciones de continuidad a los elementos almacenadores de energía:
• Condensador (C): La tensión en un condensador debe ser continua si la intensidad es finita. 
u 
C
​
 (0 
+
 )=u 
C
​
 (0 
−
 )oq(0 
+
 )=q(0 
−
 )
• Bobina (L): La intensidad que circula por una bobina debe ser continua si la tensión es finita. 
i 
L
​
 (0 
+
 )=i 
L
​
 (0 
−
 )oϕ(0 
+
 )=ϕ(0 
−
 )
4. Solución Final
La solución total, después de evaluar t=0 
+
 , se expresa como: 
D(t)=(D(0 
+
 )−D 
∞
​
 (0 
+
 ))e 
− 
τ
t
​
 
 +D 
∞
​
 (t)

--------------------------------------------------------------------------------
Ahora, para completar el proceso, necesitamos el valor de D_\infty(t) (Régimen Permanente).
D 
∞
​
 (t) es el valor de la función cuando la etapa transitoria ha terminado (t→∞).
Si la excitación g(t) es constante (DC), ¿cómo simplificamos el circuito para hallar el valor de D 
∞
​
 (t) de la tensión en un condensador (u 
C
​
 (∞)) o la intensidad en una bobina (i 
L
​
 (∞))?
(Pista: ¿Qué valor toma la derivada de una función constante, como la tensión/corriente en régimen permanente, y qué implicación tiene esto en las ecuaciones de C y L?)
