# Practica 5 - MI PRIMERA INTERFAZ DE USUARIO INTERACTIVA

## 1.2: Agregar elementos Views en el editor de Layout

## Examinar las restricciones (constraint) de los elementos

> *Abra activity_main.xml desde el panel **Proyecto > Android** si aún no está abierto. Si la pestaña Design **(diseño)** aún no está seleccionada, haga clic en ella.*

<img src="medios\1.PNG"/>  
<img src="medios\2.PNG"/>

> *Si no hay ningún blueprint, haga clic en el botón **Select design surface** de la barra de herramientas **(puede presionar la tecla B, para cambiar entre cada modo)** y elija Design + blueprint*

<img src="medios\4.png"/>

> *La herramienta **Conexión automática** también se encuentra en la barra de  herramientas. Está habilitado de forma predeterminada. Para este paso, asegúrese de que la herramienta no está deshabilitada*

<img src="medios\5.png"/>

> *Haga clic en el botón de acercar para acercar los paneles de diseño y blueprint para ver de cerca.*

<img src="medios\6.png"/>

> *Seleccione TextView en el panel del **árbol de componentes** (Component tree). El "Hello World" se resalta en los paneles de diseño y blueprint y las restricciones para el elemento TextView son visibles.*

<img src="medios\7.png"/>

> *A continuación, se muestra como establecer una restricción o constraint con el contenedor padre al lado derecho del TextView*

<img src="medios\8.png"/>

## Añadir un botón al layout

> *Comience con una pizarra limpia. El elemento TextView no es necesario, por lo que mientras está seleccionado, pulse la tecla Supr o elija Edición > Eliminar. Ahora tiene un diseño completamente en blanco*

<img
 src="medios\9.png"/>

> *Arrastre un botón desde el panel Paleta a cualquier posición de la presentación. Si coloca el elemento Button en el área media superior de la presentación, pueden aparecer restricciones automáticamente. Si no es así, puede arrastrar restricciones a la parte superior, izquierda y derecha del diseño*

<img src="medios\10.png"/>
<img src="medios\12.png"/>

> *Añada un segundo botón en la parte inferior del layout y del mismo modo cree las restricciones correspondientes con los elementos próximos a él.*

<img src="medios\11.png"/>
<img src="medios\13.png"/>

> *Pruebe borrar todos los constraints o restricciones de un elemento, seleccionando y pasando el puntero sobre este y seleccionar cleal all constraints*

<img src="medios\14.png"/>

## 1.3: Cambiar los atributos de los elementos de la interfaz de usuario

## Cambiar el tamaño del Button

> *Seleccione el botón superior en el panel Árbol de componentes.*

<img src="medios\15.png"/>

> *Haga clic en la pestaña Atributos en el lado derecho de la ventana del editor de layout.*

<img src="medios\16.png"/>

> *Haga clic en el control de ancho las veces que sea necesario; debe lograr el valor **match_constraint** para el **layout_width**.*

<img src="medios\17.png"/>

> *Realice la misma modificación para el botón inferior, el resultado es que ambos botones deben cubrir todo el ancho del constraint.*

<img src="medios\18.png"/>

> *Establezca wrap_content al layout_height, también puede usar un valor fijo de 16dp*

<img src="medios\19.png"/>

## Cambiar los atributos de Button

> *Después de seleccionar el primer botón, edite el campo ID en la parte superior del panel Atributos a **button_toast** para el atributo android: id, que se usa para identificar el elemento en el layout.*

<img src="medios\20.png"/>

> *Establezca el atributo de **background** en **@color/colorPrimary**. (A medida que ingresa @c, aparecen opciones para una fácil selección). Si no está establecido el color, hágalo en **colors.xml**.*

<img src="medios\21.png"/>
<img src="medios\23.png"/>
<img src="medios\22.png"/>

> *Establezca el atributo **textColor** en **@android:color/white**.*

<img src="medios\24.png"/>

> *Edite el atributo text en Toast.*

<img src="medios\25.png"/>

> *Selecciona el segundo botón y edite su campo **id** a **button_count**.*

<img src="medios\26.png"/>

> *Edite el atributo **text** del segundo botón a **Contar**.*

<img src="medios\27.png"/>

> *Cambie el color de texto y de fondo a los botones*

<img src="medios\28.png"/>
<img src="medios\29.png"/>

## Agregar el elemento TextView y sus atributos correspondientes

> *Desde el panel **Palette** y el apartado Common, agregue un elemento **View TextView** y establezca el atributo **id** a **show_count**.*

<img src="medios\30.png"/>
<img src="medios\31.png"/>

> *Establezca las restricciones del **TextView**, la parte superior con el botón de **Toast** y su parte inferior con el botón contador.*

<img src="medios\32.png"/>

> *Establezca las restricciones izquierda y derecha del elemento **TextView** al lado correspondiente al contenedor padre.*

<img src="medios\33.png"/>

> *Establezca el valor **text** a **0**.*

<img src="medios\34.png"/>

> *Establezca el valor **textSize** a **160sp**.*

<img src="medios\35.png"/>

> *Establezca el **textStyle** a **bold**.*

<img src="medios\36.png"/>

> *Cambie **layout_width** y **layout_height** a **match_constraint**.*

<img src="medios\37.png"/>

> *Establezca el **textColor** a **@color/colorPrimary**.*

<img src="medios\38.png"/>

> *Establezca un valor preferido al atributo **background**, opcional el #0F49CD.*

<img src="medios\39.png"/>

> *Establezca el valor **gravity** a **center_vertical**.*

<img src="medios\40.png"/>


