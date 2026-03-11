<p align="center">
    <img src="https://github.com/rose-pine/rose-pine-theme/raw/main/assets/icon.png" width="80" />
    <h2 align="center">Rosé Pine for RMPC</h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist</p>

## Usage

1. Git clone the repository
```
git clonehttps://github.com/VigneshR387/rose-pine-rmpc.git
```
2. Each variant comes with different layouts. if you prefer the default layout of rmpc, use `rmpc_default`.
3. Move `rose-pine-(main,moon,dawn).ron` to `$XDG_CONFIG_HOME/rmpc/themes`. If you chose a custom layout, replace the fields inside the `config.ron` with ones provided in the `rmpc_default_no_border/config.ron`. Make sure there are no duplicate fields.
4. In `config.ron`, set your desired theme: `theme: "rosepine-($variant_name)"`.

> [!NOTE]
> If you have a custom layout and do not want to overwrite it, copy everything inside the theme file except the `layout` field and replace/append it to the fields in your  config theme file `$XDG_CONFIG_HOME/rmpc/themes/<your_theme_file>`. Make sure there are no duplicate fields.

## Gallery

### Rosé Pine

<img width="500" alt="Rosé Pine with rmpc" src="https://github.com/user-attachments/assets/2736a10d-d480-4b5d-ac1e-b90698ba8f1f" />

### Rosé Pine Moon

<img width="500" alt="Rosé Pine Moon with rmpc"  src="https://github.com/user-attachments/assets/1642cc72-074d-45e5-8dd6-3bff4d9a042d" />

### Rosé Pine Dawn

<img width="500" alt="Rosé Pine Dawn with rmpc" src="https://github.com/user-attachments/assets/db25af42-f3ab-4a15-be9d-8636fb4b7256" />
 />

## Bonus

### Layouts

#### Default ( No Border)

<img width="500" alt="Rosé Pine Dawn with rmpc"  src="https://github.com/user-attachments/assets/684d5bd2-182a-4896-a709-3ab132eed7cc" />
 />

#### Layout 1 ( No Border )

<img width="500" alt="Rosé Pine Dawn with rmpc" src="https://github.com/user-attachments/assets/359706d6-cbd3-4252-a7cd-7e8b6440b670" />
 />

## Thanks to

- [Rosé Pine](https://rosepinetheme.com/) for the beautiful color palette
- [rmpc](https://github.com/mierak/rmpc) for the amazing MPD client
- [CAVA](https://github.com/karlstav/cava) for the audio visualizer

## Contributing

Modify `template.json` using Rosé Pine variables, then build variants:

```sh
npx @rose-pine/build@latest
```
