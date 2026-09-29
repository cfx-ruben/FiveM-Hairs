## 📁 Directory organization

Each folder is named according to the **numeric ID** assigned to the item within the server's clothing menu list:

- **Folder format:** Names formatted to 3 digits (e.g., `001`, `012`, `038`).
- **Mapping:** The folder number corresponds directly to the menu position/ID.

### Example of equivalence

| Folder Name | ID in Clothing Menu | Description |
| :--- | :--- | :--- |
| `001` | **1** | Asset corresponding to position 1 |
| `038` | **38** | Asset corresponding to position 38 |
| `105` | **105** | Asset corresponding to position 105 |

---

## 🛠️ User Guide

1. Locate the object's numerical ID within the game or the appearance menu.
2. Add leading zeros to make it 3 digits long (e.g., ID `5` becomes `005`).
3. Place the corresponding files (textures, drawables, etc.) inside the named directory.

> **Note:** Maintaining this naming format ensures compatibility when indexing and updating files in server paths.
