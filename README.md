<!-- 
  <<< Author notes: Header of the course >>> 
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Introducción a GitHub

_Empieza a usar GitHub en menos de una hora._

<!-- 
  <<< Author notes: Start of the course >>> 
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<!--step0

La gente utiliza GitHub para construir algunas de las tecnologías más avanzadas del mundo. Ya sea que estés visualizando datos o construyendo un nuevo juego, hay toda una comunidad y un conjunto de herramientas en GitHub que pueden ayudarte a hacerlo mejor. El curso "Introducción a GitHub" de GitHub Skills te guía por todo lo que necesitas para empezar a contribuir en menos de una hora.

- **Para quién es esto**: Nuevos desarrolladores, nuevos usuarios de GitHub y estudiantes.
- **Qué vas a aprender**: Introduciremos repositorios, ramas \(_branches_\), confirmaciones de cambios \(_commits_\) y solicitudes de extracción \(_pull requests_\).
- **Qué vas a construir**: Haremos un breve archivo Markdown que puedes usar como tu [perfil README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).
- **Requisitos**: Ninguno. Este curso es una gran introducción para tu primer día en GitHub.
- **Cuánto tiempo**: Este curso consta de cuatro pasos y tardarás menos de una hora en completarlo.

## Cómo empezar este curso

1. Encima de estas instrucciones, haz clic con el botón derecho del ratón en **Use this template** y abre el enlace en una nueva pestaña.<br />
   ![Use this template](https://user-images.githubusercontent.com/1221423/169618716-fb17528d-f332-4fc5-a11a-eaa23562665e.png)
2. En la nueva pestaña, sigue las indicaciones para crear un nuevo repositorio.
   - En **Owner**, elige tu cuenta personal para alojar el repositorio.
   - Recomendamos crear un repositorio público - los repositorios privados [utilizarán minutos de Acciones](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   ![Create a new repository](https://user-images.githubusercontent.com/1221423/169618722-406dc508-add4-4074-83f0-c7a7ad87f6f3.png)
3. Una vez creado tu nuevo repositorio, espera unos 20 segundos y actualiza la página. Sigue las instrucciones paso a paso en el README del nuevo repositorio.

endstep0-->

<!-- 
  <<< Author notes: Step 1 >>> 
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1 open>
<summary><h2>Paso 1: Crea una rama</h2></summary>

_¡Bienvenida a "Introducción a GitHub"! :wave:_

**¿Qué es GitHub?**: GitHub es una plataforma de colaboración que utiliza [Git](https://docs.github.com/get-started/quickstart/github-glossary#git) para el control de versiones. GitHub es un lugar popular para compartir y contribuir al software de [código abierto](https://docs.github.com/get-started/quickstart/github-glossary#open-source).
<br>:tv: [Video: Qué es GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)

**¿Qué es un repositorio?**: Un [repositorio](https://docs.github.com/get-started/quickstart/github-glossary#repository) es un proyecto que contiene archivos y carpetas. Un repositorio lleva un control de las versiones de los archivos y carpetas.
<br>:tv: [Video: Explorar un repositorio](https://www.youtube.com/watch?v=R8OAwrcMlRw)

**¿Qué es una rama (o _branch_)?** Una [rama](https://docs.github.com/en/get-started/quickstart/github-glossary#branch) es una versión paralela de tu repositorio. Por defecto, tu repositorio tiene una rama llamada `main` y se considera la rama definitiva. Puedes crear ramas adicionales a partir de `main` en tu repositorio. Puedes utilizar ramas para tener diferentes versiones de un proyecto al mismo tiempo.

En las ramas adicionales, puedes hacer ediciones sin que afecten a la versión principal o `main`. Las ramas le permiten separar su trabajo de la rama `main`. En otras palabras, el trabajo de todos está a salvo mientras tú contribuyes.
<br>:tv: [Video: Ramas](https://www.youtube.com/watch?v=xgQmu81G1yY)

**¿Qué es un README de perfil?**: Un [README de perfil](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) es básicamente una sección "Sobre mí" en tu perfil de GitHub donde puedes compartir información sobre ti misma/o con la comunidad en GitHub.com. GitHub muestra el README de tu perfil en la parte superior de tu página de perfil.

### :keyboard: Actividad: Tu primera rama

1. Abre una nueva pestaña del navegador y navega hasta este mismo repositorio. Luego, trabaja en los pasos en tu segunda pestaña mientras lees las instrucciones en esta pestaña.
2. Navega a la pestaña **Code**.
3. Haz clic en el menú desplegable de la rama **main**.<br>
   <img alt="image showing my-first-branch entry" src="/images/my-first-branch.png"/>
4. En el campo de texto, introduce el nombre de tu nueva rama: `my-first-branch`.
5. Haz clic en **Create branch: my-first-branch** para crear tu rama.
6. ¡Continúa al paso 2!<br>
   **Nota**: Si has creado un repositorio público y quieres confirmar que has configurado correctamente tu primera rama, espera unos 20 segundos y luego actualiza esta página (desde la que estás siguiendo las instrucciones). Las [Acciones de GitHub](https://docs.github.com/en/actions) cerrarán automáticamente este paso y abrirán el siguiente.

</details>

<!-- 
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=2>
<summary><h2>Paso 2: Confirma los cambios (commit) de un archivo</h2></summary>

_¡Has creado una rama!_ :tada:

Crear una rama te permite editar tu proyecto sin cambiar la rama `main`. Ahora que tienes una rama, es el momento de crear un archivo y hacer tu primera confirmación de cambios (o _commit_).

**¿Qué es una confirmación de cambios (o _commit_)?** Un [commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits) es un conjunto de cambios en los archivos y carpetas de tu proyecto. Un commit existe en una rama.

### :keyboard: Actividad: Tu primer commit

Los siguientes pasos te guiarán en el proceso de confirmar un cambio en GitHub. Para confirmar un cambio hay que añadir primero un nuevo archivo a la nueva rama. 

1. En la pestaña **Code**, asegúrate de que estás en tu nueva rama `my-first-branch`.
2. Selecciona el desplegable **Add file** y haz clic en **Create new file** para crear un archivo nuevo.<br>
   ![create new file option](/images/create-new-file.png)
3. En el campo **Name your file...**, escribe `PROFILE.md`.
4. En el área **Edit new file**, copia el siguiente contenido a tu archivo:
   ```
   ¡Bienvenida a mi perfil en GitHub!
   ```
   <img alt="profile.md file screenshot" src="/images/my-profile-file.png"/>
5. Para los commits, es recomendable que introduzcas un mensaje breve de commit que describa los cambios que has hecho. Este mensaje ayuda a otras personas (o a tu futuro yo) a entender qué cambios has introducido en tu commit. GitHub ofrece un mensaje simple por defecto, pero vamos a cambiarlo ligeramente para practicar. Primero, introduce `Add PROFILE.md` en el primer campo de texto debajo de **Commit new file**. Después, si quieres asegurarte de qué aspecto debería tener tu pantalla, expande el desplegable de debajo.
   <details>
   <summary> Expande para ver la captura.</summary>
   <img alt="screenshot of adding a new file with a commit message" src="/images/commit-full-screen.png" />
   </details>
6. En esta lección ignoraremos los demás campos; haz clic en **Commit new file**.
7. ¡Adelante con el paso 3! <br>
    **Nota**: Como antes, puedes esperar unos 20 segundos, luego refrescar esta página (de la que estás siguiendo las instrucciones) y [GitHub Actions](https://docs.github.com/en/actions) cerrará automáticamente este paso y abrirá el siguiente.

</details>

<!-- 
  <<< Author notes: Step 3 >>> 
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

<details id=3>
<summary><h2>Paso 3: Abre una solicitud de extracción (pull request)</h2></summary>

_Buen trabajo con ese commit_ :sparkles:

Ahora que has creado un commit, es el momento de compartir tu propuesta de cambio a través de una solicitud de extracción (o _pull request_).

**¿Qué es una solicitud de extracción (o _pull request_)?**: La colaboración ocurre en un pull request. El pull request muestra los cambios en tu rama a otras personas. Este pull request va a mantener los cambios que acabas de hacer en tu rama y propone aplicarlos a la rama `main`.
<br>:tv: [Video: Introduction to pull requests](https://youtu.be/kJr-PIfLDl4)

### :keyboard: Actividad: Crea un pull request

Es posible que hayas notado después de tu commit que aparece un mensaje indicando tu reciente push a tu rama y proporcionando un botón que dice **Compare & pull request**.

![screenshot of message and button](/images/compare-and-pull-request.png)

 Si quieres, puedes hacer clic en **Compare & pull request**, y luego saltar al paso 6 de abajo. Si no haces clic en el botón, las instrucciones siguientes te guiarán en la configuración manual de la solicitud de extracción.

1. Haz clic en la pestaña **Pull requests** de tu repositorio.
2. Haz clic en **New pull request**.
3. En el desplegable **base:**, asegúrate de que está seleccionado **main**.
4. Selecciona el desplegable **compare:** y haz clic en `my-first-branch`. <br>
   <img alt="screenshot showing both branch selections" src="/images/pull-request-branches.png"/>
5. Haz clic en **Create pull request**.
6. Introduce un título para tu solicitud de extracción: `Add my first file`.
7. El siguiente campo te ayuda a proporcionar una descripción de los cambios que has realizado. Siéntete libre de añadir una descripción de lo que has logrado hasta ahora. Como recordatorio, has: ¡creado una rama, creado un archivo y hecho un commit!<br>
   <img alt="screenshot showing pull request" src="/images/Pull-request-description.png"/>
8. Haz clic en **Create pull request**.
9. ¡Continúa con el paso 4! <br>
   **Nota**: Como antes, puedes esperar unos 20 segundos, luego refrescar esta página (en la que estás siguiendo las instrucciones) y [GitHub Actions](https://docs.github.com/en/actions) cerrará automáticamente este paso y abrirá el siguiente. Como ventaja, puedes ver pruebas de las Acciones de GitHub que se ejecutan en la pestaña con la solicitud de extracción abierta. La imagen de abajo muestra una línea que puedes ver en tu pull request después de que la Acción termine de ejecutarse.<br>
   <img alt="screenshot of an example of an actions line" src="/images/Actions-to-step-4.png"/>

</details>

<!-- 
  <<< Author notes: Step 4 >>> 
  Just a historic note: The previous version of this step required responding
  to a pull request review before merging. The previous version also handled
  if users accidentally closed without merging.
-->

<details id=4>
<summary><h2>Step 4: Combina tu pull request</h2></summary>

_¡Bien hecho!_ :sunglasses:

Has creado una solicitud de extracción con éxito. Ahora puedes fusionar o combinar \(_merge_\) tu pull request.

**Qué es una _fusión_** (o _merge_): Un [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) añade los cambios en su solicitud de extracción y rama en la rama `main`.
<br>:tv: [Video: Understanding the GitHub flow](https://www.youtube.com/watch?v=PBI2Rz-ZOxU)

Como se ha indicado en el paso anterior, es posible que hayas visto que se ejecuta una acción que hace avanzar automáticamente tus instrucciones al siguiente paso. Tendrás que esperar a que termine para poder fusionar tu pull request. Estará listo cuando el botón **Merge pull request** esté verde.

![screenshot of green merge pull request button](/images/Green-merge-pull-request.png)
### :keyboard: Actividad: Fusiona el pull request

1. Haz clic en **Merge pull request**.
1. Haz clic en **Confirm merge**.
1. Una vez que tu rama ha sido fusionada, ya no la necesitas. Para eliminar esta rama, haz clic en **Delete branch**.<br>
   <img alt="screenshot showing delete branch button" src="/images/delete-branch.png"/>
2. ¡Consulta el paso **Finalizar** para ver lo que puedes aprender a continuación!<br>
   **Nota**: Como antes, puedes esperar unos 20 segundos, luego refrescar esta página (desde la que estás siguiendo las instrucciones) y [GitHub Actions](https://docs.github.com/en/actions) cerrará automáticamente este paso y abrirá el siguiente.

</details>

<!-- 
  <<< Author notes: Finish >>> 
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><h2>Finalizar</h2></summary>

_¡Enhorabuena! Has completado este curso y te has unido a la comunidad de desarrolladores_

<img src=https://octodex.github.com/images/collabocats.jpg alt=celebrate width=300 align=right>

Aquí tienes un resumen de tus logros:

- Has aprendido sobre GitHub, repositorios, ramas, commits y pull requests.
- Has creado una rama, un commit y un pull request.
- Has fusionado un pull request.
- ¡Has hecho tu primera contribución! :tada:

### ¿Y ahora, qué?

  Si quieres hacer un README de perfil, utiliza las instrucciones simplificadas que aparecen a continuación o sigue las instrucciones del artículo [Gestión de tu README del perfil](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).
  1. Crea un nuevo repositorio público con un nombre que coincida con tu nombre de usuario de GitHub.
  2. Crea un archivo llamado `README.md` en su raíz. La "raíz" significa que no está dentro de ninguna carpeta de tu repositorio.
  3. Edita el contenido del archivo `README.md`.
  4. Si has creado una nueva rama para tu archivo, abre y fusiona un pull request en tu rama.
  5. Nos encantaría ver tu nuevo perfil. ¡Comparte tu perfil en las redes sociales y etiquétanos!
  6. Por último, nos encantaría saber qué te ha parecido este curso [en nuestro foro de debate](https://github.com/skills/.github/discussions).

Consulta estos recursos para obtener más información o participar:
- ¿Eres estudiante? Echa un vistazo al [Student Developer Pack](https://education.github.com/pack).
- Haz otro curso de [GitHub Skills](https://github.com/skills).
- Lee los documentos de inicio de GitHub (https://docs.github.com/en/get-started).
- Para encontrar proyectos a los que contribuir, consulta [GitHub Explore](https://github.com/explore).

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
