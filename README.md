```kotlin
class ShinYubin {
  val firstName = "Yubin"
  val lastName = "Shin"
  val name = "$firstName $lastName"
  
  var age: Int = 22 // Born in 2001

  val gender: String = "female"

  var interest: String? = "Backend Engineer"

  var study = mapOf(
      "major" to "Computer Engineering"
  )
  
  var address: String? = "Seoul, Republic of Korea"

  fun skill(): void {
    var language = arrayOf(
      "java", 
      // "kotlin"
    )

    @Stable
    var backend = arrayOf(
      "Spring Boot",
      "Spring Data JPA",
      "MySQL"
    )

    @Deprecated("This skill was deprecated")
    var deprecatedLanguage = arrayOf(
      "c/cpp", 
      "javascript"
    )
    @Deprecated("This skill was deprecated")
    var front = arrayOf(
      "react", 
      "vuejs"
    )

    var ci = arrayOf(
      "Github Actions"
    )
  }

  fun tools(): void {
    var textEditor = arrayOf(
      "Visual Studio Code"
      // "Atom"
    )
    var ide = arrayOf(
      "IntelliJ IDEA", 
      "DataGrip",
      "Web Storm"
    )
  }

  fun contact(): void {
      var email: String = "dbqls2821@gmail.com"
      var blog: Stirng = "https://valley-fog-37a.notion.site/e036f53827ce4b3e84513c38e1c0afdd?pvs=4"
      var github: String = "https://github.com/shinyubin989"
  }
}
```
	   
 
