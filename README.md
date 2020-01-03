# dmenu-translation

Software gets a word or a phrase by dmenu then makes a request to the "Yandex.Translate" service and backs translation to the dmenu.

At this moment it works only with english and russian languages and I have no plans to add any other.

# Dependencies

```
cpan install \
    LWP::UserAgent \
    LWP::Protocol::https \
    JSON::XS
```
