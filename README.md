# Rajan Bor

```go
type ChillGuy struct {
    Currently  []string
    Interests  []string
    Philosophy string
}

func main() {
    me := ChillGuy{
        Currently: []string{
            "developing boringcode.com",
            "building AI workflows",
            "contributing",
            "learning",
        },

        Interests: []string{
            "automation",
            "security",
            "developer tools",
            "weird AI ideas",
        },

        Philosophy: "boring code > clever code",
    }

    ship(me)
}
```
