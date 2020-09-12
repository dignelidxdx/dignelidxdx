### Hola a todos.. Soy Digneli Dávila, Ingeniera Industrial y Programadora Jr. Tengo 25 años 👋 Amo aprender y compartir conocimientos ⚡.
![Intro](https://firebasestorage.googleapis.com/v0/b/my-portfolio-2a204.appspot.com/o/Digneli%20D%C3%A1vila.png?alt=media&token=bcb1bc66-d06c-423c-89b6-04ef0e91f7f3)

Reach me on: [![Linkedin: Digneli](https://img.shields.io/badge/-Digneli-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/digneli-davila/)](https://www.linkedin.com/in/digneli-davila/)
Portfolio: <https://dignelidavila.com>.


## Tech Stack:

```Java
public static void main(String[] args) {
		SpringApplication.run(ApiApplication.class, args);
		creatingNewDev();
	}

	public static void creatingNewDev() {
		
		List<Frontend> fSkills = new ArrayList<>();
		Frontend frontend = new Frontend("ReactJS", "Redux", "Bootstrap");
		fSkills.add(frontend);

		List<Backend> bSkills = new ArrayList<>();
		Backend backend = new Backend("Microservices", "Spring-boot", "Maven", "JWT", "WebAPI");
		bSkills.add(backend);

		List<Hobby> hobbies = new ArrayList<>();
		Hobby hob = new Hobby("Excersite", "Play Video Games", "Read, Study and Listen to Music");
		hobbies.add(hob);	

		Developer developer = new Developer("Digneli Dávila", 25, "Buenos Aires", fSkills, bSkills, hobbies);
		
		String[] otherSkills = {"SQL", "JUnit", "Mockito", "Sonarqube"};

		System.out.println(developer);
	}
```
<em><b> Output: </b></em>
```Java
Name: Digneli Dávila. Age: 25 Address: Buenos Aires
Frontend Skills: [My main frontend skill: ReactJS. Second: Redux. Third: Bootstrap.]
Backend Skills: [My main backend skill: Microservices. Second: Spring-boot. Third: Maven. Fourth: JWT. Fiveth: WebAPI.]
Hobbies: [My favorite hobbies are: Excersite, Play Video Games, Read, Study and Listen to Music.]
```
<em><b>Mi día a día es como un libro ✨ , me encanta aprender nuevas cosas y llevarlas a la práctica como también enseñarlas. Siempre me sumo a nuevos retos y trato de dar lo mejor de mi, no conozco un "no se puede" en mi vocalulario diario </b> :)</em>

<!--
**dignelidxdx/dignelidxdx** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
