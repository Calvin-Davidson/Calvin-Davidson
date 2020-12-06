```java
public class Croyke extends GitHubUser {

  public Croyke() {
    super("Croyke", "Netherlands");

    this.addLanguage("Java", "C#", "Javascript", "c++", "html", "css");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> languages = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... language) {
    languages.addAll(language);
  }
}
```

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Calvin-Davidson&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
    <td>
      <img src="https://wakatime.com/share/@e837145a-31e5-48fd-ae85-70bcf7426b10/b55d74c9-3719-45de-98ba-1b0c6ec2f52e.svg" alt="wakatime stats" height=195>
    </td>
  </tr>
</table>
