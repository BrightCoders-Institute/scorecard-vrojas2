![BrightCoders Logo](assets/images/logo-bc.png)

# Scorecard

El propósito de este documento es tener un perfil completo de cada uno de nuestros BrightCoders. Por favor, proporciona tanta información como te sea posible.

## Pre-requisitos

Antes de iniciar debes contar con una evaluación oficial de tu nivel de inglés. Si ya la tienes sube el resultado de tu evaluación en la carpeta [certificate](/certificate)

Si no lo tienes [realiza está evaluación de manera gratuita](https://www.efset.org/ef-set-50/) y una vez que termines sube tu certificado. Requerirás de 50 minutos aproximadamente para realizarla.

## Instrucciones

Actualiza el archivo [_data/data.yml](_data/data.yml) con tu información, siguiendo las indicaciones que a continuación se presentan.

Puedes modificar el archivo directamente desde aquí en GitHub o descargarlo en tu computadora y subir la actualización (utilizando git).

## Habilitar GitHub Pages

1. Ve al apartado de `settings` de este repositorio.
2. Ubica el apartado  `Github Pages`
3. En `source` selecciona `Deploy from branch`
4. En `branch` selecciona 'main' y la carpeta `root`
5. Espera un momento a que se publique, refresca tu navegador para ver actualizaciones. Una vez que se publique te aparecerá la url asociada a tu GitHub Pages.
6. Copia la `url` que se generó.
7. Regresa a la sección `Code`, edita el archivo `_config.yml` modificando el campo `baseurl:` con la dirección que tu GitHub Pages generó.

Con esto se publicará tu repositorio y en esa dirección podrás revisar las actualizaciones que hagas. Es importante que cada que hagas una modificación revises como se actualiza tu página ya que podrías generar algunos errores.

# Modificaciones en el archivo `_data/data.yml`

## Nombre

1. Ubica el apartado `name` y escribe tu primer nombre y apellido, por ejemplo: John Doe

## Programa

1. Ubica el apartado `tagline` y escribe según corresponda:
   - Ruby on Rails Web Developer
   - React Native Mobile Developer

## Datos de contacto

1. Ubica el apartado `email` y completa todos los datos de contacto que quieras registrar:

   - Phone
   - website
   - linkedin
   - github
   - bitbucket
   - twitter
   - stack-overflow
   - codewars
   - goodreads
  
## Idiomas

1. Ubica el apartado `languages`.
2. Incluye todos lo idiomas que sabes así como el nivel de dominio. Para el nivel utiliza:
   - Si es tu lengua nativa puedes indicarlo como Native.
   - Indica el resultado de una evaluación oficial como IELTS, TOEFL, [EF-SET](https://www.efset.org/ef-set-50/) e indica el nivel o puntos obtenidos.
   - Si **no** tienes alguna evaluación utiliza el modelo **Dreyfus** (este modelo se explica al final de este documento).

## Soft skills

1. Ubica el apartado `interests`.
2. Agrega un soft skill en cada `item`.
  
Los Soft Skills son competencias o habilidades sociales que son fundamentales para relacionarse con otras personas ya sea en la vida diaria o en el trabajo, como por ejemplo la comunicación, el trabajo en equipo, adaptabilidad, creatividad, pensamiento creativo, solución de problemas, confianza, administración del tiempo, personas o tareas, colaboración, etc.

Estas son algunas de las soft skills que más valoran los empleadores:

- [Soft Skills for Developers – The Ultimate Guide](https://pointjupiter.com/soft-skills-software-developer-need-ultimate-guide/)
- [10 Soft Skills Every Developer Needs](https://hackernoon.com/10-soft-skills-every-developer-needs-66f0cdcfd3f7)
- [Top Soft Skills for Developers and Programmers in 2021](https://medium.com/aslisachin/top-soft-skills-for-developers-and-programmers-in-2020-62b8d663df01)
- [Important Soft Skills for Information Technology (IT) Jobs](https://www.thebalancecareers.com/top-information-technology-it-soft-skills-2063781)
- [Critical soft skills for software developers](https://medium.com/swlh/critical-soft-skills-for-software-developers-6845545f6dbd)

## Acerca de Mí (About Me)

1. Ubica el apartado `career-profile`.
2. En el campo `summary` escribe un resumen de tu perfil, por ejemplo:

As a Computer Systems Engineering student with a deep passion for technology and programming, I have a keen interest in robotics, IoT, artificial intelligence, and their applications in various fields such as agriculture. As an autodidact programmer, I have a love for learning and consistently seek to improve my skills by staying up to date with industry best practices and logical thinking. I am proactive, diligent, and thrive in collaborative environments, where I can share my knowledge and learn from others. My passion for technology stems from my belief that it has the potential to make us better individuals, coworkers, and productive members of society. As a future Senior Developer, I am looking for an innovative company here in Mexico, where I can leverage my creativity and problem-solving skills to make an impact in people's lives.

## Educación

1. Ubica el apartado `educationcomplete`.
2. Registra los estudios realizados más relevantes, pueden ser formales, informales, certificaciones, etc.

## Experiencia

1. Ubica el apartado `experiences`.
2. Registra los proyectos o trabajos en los que has participado. Pueden ser proyectos escolares.
3. En el campo `details` asegúrate de proporcionar información suficiente para conocer sobre el proyecto, incluso puedes agregar el enlace al repositorio del proyecto o producto desarrollado,

## Technical Skills

1. Ubica el apartado `skills`.
2. Registra la siguiente información para cada tecnología:
   1. `name:`  El nombre de la tecnología, por ejemplo: ruby, rails, react, etc.
   2. `level:` Indica el porcentaje de acuerdo a los siguientes parámetros:
      - 20% para Novice
      - 40% para Advanced beginner
      - 60% para Competent
      - 80% para Proficient
      - 100% para Expert  
   3. `level-name:` Según corresponda:
      - Novice
      - Advanced beginner
      - Competent
      - Proficient
      - Expert
   4. `time:` tiempo que llevas trabajando con esa tecnología:
      1. `6 months` para 6 meses o menos
      2. `1 year` para más de 6 meses y hasta 1 año
      3. `1.5 years` para más de 1 año y hasta 1.5 años
      4. `2 years` para más de 1.5 años y hasta 2 años
      5. `2+ years` para más de 2 años

## Tecnologías

Considera incluir las siguientes y otras tecnologías:

Programming Languages | Javascript | Styling | Markup / Templating
----------------------|------------|---------|-------------
Ruby | Javascript | CSS | HTML
Ruby on Rails | Typescript | Sass | HAML
Java | React | LESS | ERB
Python | React Native | Stylus
Go | Angular
PHP | Vue
C# | NodeJs

Databases | Command Line | Testing | Continuous Integration
----------------------|------------|---------|-------------
SQL Databases | Shell | Rspec | Jenkins
Non-SQL Databases | Bash | Minitest | Circle CI
SQL Queries | | Capybara | Travis CI
 _ | _ | Cypress | GitHub Actions
 _ | _ | Jest | Docker
 _ | _ | Mocha JS | Kubernetes
 _ | _ | Jasmine
 _ | _ | Puppeteer

Version Control | Cloud Platforms | Project Management 
----------------------|------------|---------
Git | AWS | SCRUM
 _ | Google Cloud Platform
 _ | Microsoft Azure
 _ | IBM Cloud

## El modelo Dreyfus

Fases de adquisición de habilidades:

- `Junior Developer (1-3 años)`
  - `Novice.` Poca experiencia, se guían por se sigan reglas, técnicas, instrucciones y procedimientos, tienen dificultades para reaccionar ante los errores
  - `Advanced Beginner.` Ya tienen algo de práctica o experiencia, comienzan a liberarse de seguir reglas o instrucciones, aún  tiene dificultades para resolver problemas por cuenta propia
- `Middle Developer (3-5 años)`
  - `Competent.` Han dedicado un tiempo considerable a practicar, pueden resolver problemas y trabajar de manera independiente e incluso mentorear a novatos, buscan y aplican consejo de expertos.
- `Senior Developer  (5+ años)`
  - `Proficient.` Pueden entender el contexto más amplio y lo necesitan para guiar su trabajo, puede extraer información relevante de la experiencia de otros en lugar de tomarla como un todo
  - `Expert.` Son la principal fuente de conocimiento, trabajan desde la intuición, intuyen las mejores prácticas a partir de su amplia gama de experiencia con diferentes roles, tecnologías y situaciones

Para entender mejor el modelo Dreyfus e identificar en que nivel te encuentras utiliza los siguientes recursos:

- [How To Evaluate Expertise: the Dreyfus Model](https://www.solcept.ch/en/blog/dreyfus-model/)
- [Building Software Development Expertise – Using The Dreyfus Model](https://skorks.com/2009/08/building-software-development-expertise-using-the-dreyfus-model/)
- [Software Engineer Qualification Levels: Junior, Middle, and Senior](https://hackernoon.com/software-engineer-qualification-levels-junior-middle-and-senior-f2229591df1c)

## Recursos
- [How to write a killer Software Engineering résumé](https://www.freecodecamp.org/news/writing-a-killer-software-engineering-resume-b11c91ef699d/)

