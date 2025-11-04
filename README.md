```kotlin
fun getAbout(): AndroidDeveloper {
    val fullName = "Patryk Miś"
    val description = """
        I care about making technology work for everyone. My main focus is Android accessibility and building open-source screen readers that give real independence to users who rely on them.

        📱 Android Accessibility
        I explore how Android can be more inclusive - from accessible UI design to improving system-level interaction for assistive tech users.

        🌐 Open-Source Screen Readers
        I support the open software movement by contributing to free, community-driven screen reader projects. The goal is simple: open code, open access, equal opportunity.

        Technology should serve people - all people.
    """.trimIndent()

    val skills = mapOf(
        "HTML" to "2007 ~ Today, from 4.01 Strict to WHATWG HTML Living Standard",
        "ARIA" to "2015 ~ Today, evolving WAI-ARIA spec",
        "Kotlin" to "basic",
        "Java" to "basic",
        "C/C++" to "basic",
        "Rust" to "basic",
        "Python" to "basic"
    )

    return AndroidDeveloper(fullName, description, skills)
}
```
