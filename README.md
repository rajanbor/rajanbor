# Rajan Bor (izqzmyli)
{"someday i will write here something more"}

```go
type rajan_bor struct {
    Role        Role
    GitHub      GitHub
    Email       Email
    Website     Website
    X           X
    Company     Company
    Philosophy  string
    TechStack   []Technology
    Learning    string
}

func (r *rajan_bor) New() *rajan_bor {
    return &rajan_bor{
        Role:       Role.FULL_STACK_DEVELOPER_AND_FOUNDER,
        GitHub:     GitHub{"github.com/izqzmyli"},
        Email:      Email{"rajan.bor@pm.me"},
        Website:    Website{"rajanbor.com"},
        X:          X{"x.com/rajanbor"},
        Company:    Company{"boringcode.com"},
        Philosophy: "boring code > clever code",
        TechStack:  []Technology{
            "Python", "TS", "JS", "Rust basics",
        },
        Learning: "Go, more Rust",    
    }
}
```
