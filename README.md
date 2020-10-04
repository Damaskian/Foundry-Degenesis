# **Degenesis-Sandbox-FoundryVTT**

Ficha de Degenesis hecha en Sandbox para Foundry VTT

**IMPORTANTE:** Necesitas tener instalado el sistema '[sandbox](https://gitlab.com/rolnl/sandbox-system-builder/-/tree/master)' instalado en Foundry. Una vez instalado, inserta la URL de este ([World.json](https://raw.githubusercontent.com/Damaskian/Foundry-Degenesis/main/world.json)) en Foundry VTT > Game Worlds > Install World > Manifest URL: LINK

Gracias Seregras ([@Rol_NL](https://twitter.com/Rol_NL)) por crear semejante herramienta con la que perder la cabeza haciendo fichas para los que no sabemos programar.



Cualquier duda que tengáis, puedes contactarme vía twitter ([@Regik](https://twitter.com/Regik)) y si quieres apoyarme económicamente para que pueda seguir comprando manuales de rol, puedes invitarme a un café: 

## **[Ko-Fi!](https://ko-fi.com/regik)**



#### **¿Qué es lo que puedes hacer con la ficha?**

- **Pestaña Atributos y Habilidades:**

  - Tiradas de Atributos + Habilidades con resultado de éxitos y fracasos automáticos. También cuenta los DT de cada tirada.
  - Rangos: Con solo arrastrar el rango correspondiente del compendio, se añadirá a la ficha todo el equipamiento que contenga dicho Rango. No está completo pero es funcional.
  - Campo para LC/Dinares.
  - Elegir entre Concentración/Primordial y Fe/Voluntad.
  - Ego, Esporas, Heridas y Traumas se ajustan automáticamente dependiendo de los Atributos + Habilidades que establezcas. 
    - Esporas: Tienes un botón para la resistencia a las esporas y también un medidor para las Esporas permanentes que se ajusta automáticamente al 50% de tu total de esporas.

- **Pestaña de combate:**

  - Tirada de Iniciativa (PSI + Reacción)
  - Modificador: Aquí añades una suma o resta del total de dados a tirar. ¿Gastas ego para tener +3D a la Iniciativa? Pones +3. ¿Tienes -2D por la impedimenta? Pones -3. Todas las tiradas de la ficha tendrán aplicado el modificador automáticamente, asegúrate de tenerlo siempre a 0 si no tienes ningún penalizador/beneficio.
  - Impedimenta: Se calcula automáticamente el máximo que puedes llevar y el total que tienes actualmente.
  - V. Protección: Se calcula automáticamente dependiendo de la armadura/potencial que te equipes.
  - Panel de Defensa Activa:  4 botones para cuando actives tu defensa en combate.
  - Tabla de Armas: Arrastrando el arma a la ficha, se colocan todos los datos necesarios de dicha arma, su tirada y su daño está todo calculado. Solo debes cambiar la munición manualmente (por ahora).
  - Tabla de Armas Sónicas: Esta tabla está oculta, en el momento que te equipes un arma sónica, aparecerá con sus correspondientes tiradas de INT + Ingeniería y PSI + Dominación.
  - Tabla de Agentes: Tabla oculta hasta que te equipes un Agente.
  - Tabla de Armaduras. Arrastrando la armadura del compendio, se ajustará automáticamente el V. de la Protección e impedimenta.
  - Tabla de Potenciales: Arrastrando el potencial y voilá! Poco a poco iré añadiendo todos los potenciales.
  - Plantillas en el Compendio: Si echas en falta algún arma, potencial, armadura... Etc puedes utilizar las plantillas. Lo duplicas y en el nuevo, modificas sus características. Esto es solo válido para el Gamemaster.

- **Perfil de Combate de NPCs:**

  - Características:
    - Iniciativa: Pones el número de dados que debe tirar el NPCs.
    - Ego: El Ego que tiene el NPC, de aquí restas y lo añades al Modificador.
    - Heridas y Trauma: Automáticamente se ajustará en el panel 'Info' para que tengas rápidamente una visual de la vida total del NPC.
  - Combate: 
    - La parte de Defensa Activa, en cada apartado ponéis el nombre del movimiento y la cantidad de dados a tirar con el botón.
  - Especialidad:
    - Esto es una tabla. En la carpeta 'Compendio NPCs' tenéis plantillas para añadir las Especialidades de cada NPCs.
  - Especial:
    - Aquí irían los Equipos Especiales o Defensas Especiales de los NPCs.
  - Ataques:
    - Esto es otra tabla. En 'Compendio NPCs' tenéis las plantillas para los ataques.
  - Protecciones y Anotaciones:
    - Aquí añadís las protecciones usando las plantillas y también tenéis un campo para añadir información extra del NPC.

  

### **¿Qué estoy trabajando actualmente?**

- Automatizar aún más la ficha.
- Mejorando el estilo visual.
- Añadiendo todos los Rangos, Potenciales. 
- Ampliando Compendio de NPCs.
- Añadiendo Journals del sistema Degenesis.
