## 🌿 Nommage des Branches (Git Flow)

Toute modification doit être effectuée sur une branche dédiée avant d'être fusionnée via une **Pull Request** vers `main`.

**Format :** `[type]/[description]`

| Type        | Description                                  |
|:------------|:---------------------------------------------|
| `feat/`     | Nouvelle fonctionnalité                      |
| `fix/`      | Correction d'un bug                          |
| `ci/`       | Changement de CI/CD                          |
| `docs/`     | Documentation (Markdown, Javadoc)            |
| `refactor/` | Amélioration du code sans changer la logique |
| `test/`     | Ajout ou modification de tests               |
| `chore/`    | Maintenance (dépendances, config Maven)      |

---

## 📝 Messages de Commit (Conventional Commits)

Nous utilisons la norme **Conventional Commits 1.0.0**. Cela permet une lecture claire de l'historique et la génération automatique de changelogs.

**Format :** `[TYPE]([SCOPE]): [description en minuscule]`

- **TYPE :** Doit être l'un des types définis pour les branches (feat, fix, docs, etc.).
- **SCOPE (optionnel) :** La partie du système impactée entre parenthèses (ex: `security`, `db`, `api`).
- **Description :** Une phrase courte au présent, sans majuscule initiale et sans point final.
