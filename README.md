### Hi there 👋 I'm PastelRobots!

- 🔭 I’m currently working on my minecraft server CubeMC
- 👯 I’m looking to collaborate on minecraft plugins and discord vots
- 🤔 I’m looking for help with coding support.
- 😄 Pronouns: He/Him
- 📫 How to reach me: 
### My Contacts!
* My Discord: Pastel#2032
* Email: pastelrobotthrowaway@gmail.com (Don't worry this is **NOT** a throwaway email, it was what it was intended to be in the first place until I decided to turn it into a way to reach me)

```
  public class PastelRobots extends AboutMe implements Youtuber, Coder {

	@Override
	public String getIRLName() {
		return "Aidan";
	}
  
  	@Override
	public String gamesIPlay() {
		return "I like to play minecraft and fnf.";
	}
	
	@Override
	public List<String> getWhatYouCanCallMe() {
		return Arrays.asList("Pastel", "Aidan", "Robots", "Literally anything else!");
	}

        public Me() {
        super("Pastel", "Earth");

        this.addCodeLanguage("Java", "Python", "Javascript");
        this.addExperience("1 year Java", "4 years Python", "2 years Javascript");
     }
   }
   
  @Override
	public void codingProgress() {
		String[] learning = ["Experienced Server Plugins / PVP Clients / Java", "Discord Bots / Node.js", "Making fun little programs / Python"];
		String[] tryingTo = ["Improve Pastel client". "Make good server plugins"];
	}

} 


public abstract class AboutMe {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubProf(String username, String placeilive) {
      this.name = username;
      this.country = placeilive;
  }

  public void addCodeLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
