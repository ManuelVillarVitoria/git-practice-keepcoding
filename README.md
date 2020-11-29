# `Práctica de GIT y Github`


## Preguntas & Respuestas ✒️

1. **¿Qué comando utilizaste en el paso 11? ¿Por qué?**<br />
   
<code>git reset --hard HEAD</code> (Para volver a la posición del commit anterior y deshacer los cambios de código)<br /><br />

2. **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**<br />

<code>git reflog</code> (para mostrar todos los movimientos del HEAD y ver el commit donde aún no se habían desecho los cambios)<br />
<code>git reset --hard 0772dbe</code>(para reahcer el último commit posicionando el HEAD en el Hash '0772dbe' y recuperar así los cambios)<br /><br />

3. **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**<br />

No. Porqué el código de *master* no afectaba al código de la rama *styled* <br /><br />


4. **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**<br />

Si. Porque el fichero es pequeño y se ha modificado código muy cercano del fichero, en este caso el fichero entero en la rama </br>*htmlify* que afecta al código de la rama *styled* y GIT no sabe que código nos queremos quedar <br /><br />

5. **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**<br />

No. Porqué el código de *styled* no afectaba al código de la rama *master* <br /><br />


6. **¿Qué comando o comandos utilizaste en el paso 25?**<br />

 <code>git log --graph --pretty=oneline</code> <br />
 Para personalizar el comando de forma sencila a nivel global: <br />
 <code>git config  --global alias.graph "log --graph --pretty=oneline</code> <br />
 <code>git graph</code> <br /><br />

7. **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**<br />
    Si podría serlo porque no hubo conflicto, simplemente no  preguntaría, haría el merge directamente<br /><br />

8. **¿Qué comando o comandos utilizaste en el paso 27?**<br />

    <code>git reset HEAD~1</code> <br /><br />

9. **¿Qué comando o comandos utilizaste en el paso 28?**<br />

    <code>git reset --hard HEAD</code> <br /><br />


10. **¿Qué comando o comandos utilizaste en el paso 29?**<br />

    <code>git branch -D title</code> <br /><br />


11. **¿Qué comando o comandos utilizaste en el paso 30?**<br />

    <code>git reflog</code> <br />
    <code>git reset --hard 82915a2</code> <br /><br />


12. **¿Qué comando o comandos usaste en el paso 32?**<br />
    <code>git reflog</code> <br />
    <code>git reset --hard a0832bd </code> <br /><br /> 

13. **¿Qué comando o comandos usaste en el paso 33?**<br />
    <code>git reflog</code> <br />
    <code>git reset --hard 82915a2</code> <br /><br /> 




## Expressions of gratitude 🎁

* First of all, I thank the only true God, Father, Son and Holy Spirit. <br />
"For from him and through him and for him are all things. <br />
To him be the glory forever! Amen. <br />
<code>(Romans 11:36)</code> 📢

---
⌨️ with ❤️ by [ManuelVillarVitoria](https://github.com/ManuelVillarVitoria) 😊

