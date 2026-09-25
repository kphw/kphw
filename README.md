```c
typedef struct {
    const char *github;
    const char *discord;
    const char *languages[];
    const char *interests[];
    const char *status;
} Uriel;

Uriel uriel = {
    .github = "kphw",
    .discord = "fakeconfess",

    .languages = {
        "C",
        "Javascript",
        "Python",
    },

    .interests = {
        "Discord Bots",
        "Automation",
        "Discord Selfbots",
    },

    .status = "Always thinking of something new."
};
```
