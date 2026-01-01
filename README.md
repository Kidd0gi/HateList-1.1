# Welcome to the Geometry Dash Shitty List template!

# FAQ

---

### Website FAQ

Can I use the Shitty List template?

- Sure. Credits to the shitty list are embedded onto this template so keep that in.

The website isn't loading! What can I do?

- Since no webhost is perfect, downtime is expected. You can either wait till the
  website is back online or you can do some behind the scene stuff and run it
  locally.

---

### Usage FAQ

How do I add items to the list?

- Create a new JSON file in the `data/` folder (example: `My_Hated_Thing.json`). Each item should contain at least the `name` field. Optional fields are `description` (short text), `link` (a URL), and `image` (path to an image file).

- Files should NOT have a numeric prefix in their filename; the list order is controlled from `data/_list.json`. You can update `_list.json` manually (use the filename base without `.json`, e.g. `"My_Hated_Thing"`), or run the script `.scripts\build_list.ps1` to regenerate the list from files in `data/`.

How do I add records to the list?

- Again, use one of the given templates, and modify the details accordingly. For mobile
  records, you can add the code `mobile: true` within the braces. Make sure there are no
  excess or missing commas, or the website might not load properly.

What are some common reasons for the website not loading?

- The most common cause is missing commas and inverted commas, or extra commas at the end of
  the last lines within list entries. A good way to find the error-causing lines can be found
  by using `Inspect Element` and going to the `Console` tab.

---

## More Coming Soon!

## Repo Maintainers:

- Prometheus
- Emonadeo
