# 🌊 Cayla

Hi, my name is Cayla! I'm a passionate **7-year self-taught programmer** who often contributes to open-source projects.

```py
from dataclasses import dataclass
from typing import Literal

type KnownLanguage = Literal["Python"] | Literal["Luau"]

@dataclass
class Cayla():
    """
    Information about me!

    Parameters
    ----------
    best_language: KnownLanguage
        The language I work the best with.
    languages: list[KnownLanguage]
        A list of languages I work the best with.
    website: str
        My portfolio!
    """

    best_language: KnownLanguage = "Python"
    languages: list[KnownLanguage] = ["Python", "Luau"]
    website: str = "https://cayla-portfolio.carrd.co/"

cayla = Cayla()
```
