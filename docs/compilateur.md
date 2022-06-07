# Compilateur

Eclipse est développé en [Java](https://www.java.com/fr/), qui est un [Langage Compilé](https://en.wikipedia.org/wiki/Compiled_language).

Il faut donc que votre code soit converti en `aspire.jar` pour pouvoir l'exécuter. On utilise, un compilateur. 


## Configurer le compilateur

	1. Cliquez sur **run**, puis **Run Configurations**.
	2. Dans la fenêtre qui s'ouvre, choisissez **Java**, puis **Java Application**.
	3. Séléctionnez la configuration crée, et dans le champ **Main Class**, entrez **gov.imint.aspire.main.Main**.
	4. Assurez vous que JRE/Runtime JRE est bien sur **"Project JRE"**
	5. Cliquez sur **Apply, puis fermez.**.


## Compiler un projet

    1. Cliquez droit sur le projet, puis **Export** 
    2. Dans la fenêtre ouverte, séléctionnez **Java**, puis **Runnable JAR file**. 
    3. Cliquez sur suivant, choisissez la configuration puis la destination, et cliquez sur **Finish**.

    