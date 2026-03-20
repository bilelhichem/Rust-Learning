## CARGO.TOML

 C'est le fichier de configuration (le "Manifest"). Vous y listez le nom de votre projet, sa version et toutes les bibliothèques externes que vous voulez utiliser


 ##  Cargo.lock

 Ce fichier est généré automatiquement. Il garantit que n'importe qui compilant votre projet utilisera exactement les mêmes versions de bibliothèques que vous, assurant une reproduction parfaite du build

## src/main.rs

C'est là que réside votre code source.


# 🦀 Apprentissage de Rust : Les Primitives



| Concept | Syntaxe | Le "Secret" à retenir |
| :--- | :--- | :--- |
| **Variable Immuable** | `let x = 5;` | **Fixe.** On ne peut pas changer la valeur après création. |
| **Variable Mutable** | `let mut x = 5;` | **Flexible.** Le mot `mut` autorise la modification. |
| **Shadowing** | `let x = 5; let x = true;` | **Remplacement.** On recrée une variable qui "écrase" l'ancienne. |
| **Inférence** | `let x = 10;` | **Intuitif.** Rust devine le type (ici `i32`) selon le contexte. |
| **Entier** | `i32`, `u64`, `5i8` | `i` = avec signe (+/-), `u` = positif seulement. |
| **Flottant** | `f32`, `f64` | Nombres à virgule (`f64` par défaut). |
| **Booléen** | `bool` | Uniquement `true` ou `false`. |
| **Tuple** | `(5, true, 1.2)` | **Mélange.** Plusieurs types différents groupés. |
| **Array (Tableau)** | `[1, 2, 3]` | **Uniforme.** Même type et taille fixe. |

---
