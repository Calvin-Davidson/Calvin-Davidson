```java
public class Croyke extends GitHubUser {

  public Croyke() {
    super("Croyke", "Netherlands");

    this.addLanguage("Java", "C#", "Javascript", "c++", "html", "css");
    this.addSoftware("Unity", "jetbrains rider");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> languages = new ArrayList<>();
  private ArrayList<String> software = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... language) {
    languages.addAll(language);
  }
  
  public void addSoftware(String... software) {
    software.addAll(software);
  }
}
```

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Calvin-Davidson&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
  </tr>
</table>
