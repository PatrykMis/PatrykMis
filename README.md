```kotlin
fun getAbout(): AndroidDeveloper {
    val fullName = "Patryk Miś"
    val description = """
        Passionate about fostering inclusivity in technology, my focus revolves around enhancing Android accessibility and pioneering the development of fully open-source screen readers. With each line of code, I aim to bridge the digital divide, ensuring that every user, regardless of ability, can navigate and interact seamlessly with digital interfaces.

        📱 Android Accessibility:
        Diving deep into the realms of Android development, I am dedicated to crafting accessible solutions that empower users with diverse needs. From exploring inclusive UI/UX design to implementing accessibility features, my goal is to contribute to a more accessible Android ecosystem.

        🌐 FLOSS Screen Readers Development:
        Championing the principles of Free and Libre Open-Source Software (FLOSS), I actively contribute to the development of screen readers that break down barriers. By embracing openness and collaboration, my work aims to create a more transparent and accessible digital experience for everyone.

        Let's code for a future where technology truly serves all! 🚀
    """.trimIndent()

    val skills = mapOf(
        "HTML" to "2007~Today, 4.01 Strict ~ 5.2",
        "ARIA" to "2015 ~ Today, 1.0 ~ 1.2", // Accessible Rich Internet Applications
        "Kotlin" to "basic",
        "Java" to "basic",
        "C/C++" to "Basic"
    )

    return AndroidDeveloper(fullName, description, skills)
}
```
