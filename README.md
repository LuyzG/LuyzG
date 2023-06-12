```ts
class Developer {
  constructor(
    private readonly languages: string[],
    private readonly interests: string[],
  ) {}
}

class MySelf extends Developer {
  private name: string;
  private local: string;

  constructor() {
    const interests = ["HTML", "CSS", "JavaScript", "NodeJS"];
    const languages = ["PHP", "SQL"];
    super(
      languages,
      interests,
    );
    this.name = "Luiz Gabriel";
    this.local = "Brazil";
  }
}

const me = new MySelf();

console.log(me)
```
<!---
LuyzG/LuyzG is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
