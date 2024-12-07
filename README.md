# simpleR

![version](https://img.shields.io/badge/version-1.1-green)

![header](docs/README/header.png)

- [simpleR](#simpler)
    - [Getting Started](#getting-started)
    - [Base Framework Parts](#base-framework-parts)
    - [Features](#features)
        - [Small Range of Parts](#small-range-of-parts)
        - [Scalable](#scalable)
        - [Flexible](#flexible)
        - [Easily Printable](#easily-printable)
        - [Rigid](#rigid)
        - [Modifiable](#modifiable)
        - [Nuts as Inserts](#nuts-as-inserts)
        - [Modular](#modular)
    - [Prototypes](#prototypes)
    - [Example Projects](#example-projects)
    - [Branding](#branding)
    - [License](#license)

A mechanical robotic framework designed for research, education, and fun.

The core concept of the framework is the **platform**. A platform is a flat plate that can support mechanics and electronics. These platforms are connected by vertical bars and can be covered with shells. Below is the complete list of base parts:

- **Platform**: Interchangeable square-shaped plate that can support mechanics and electronics.
- **Bar**: Vertical structural element that connects the platforms: 3 variants. The variants have different lengths designed to be used with differenet amount of platforms - from 1 to 3. You need 4 bars per project.
- **Shell**: Platform walls with open top. (3 variants)
- **Lid**: Cover for shells.

All parts are designed for easy modification, extension, 3D printing, and assembly.

The framework includes both base platforms and **prototypes** build on using base platforms. The prototypes are more specialized parts that can be used for specific custom assemblies:

![parts](docs/README/parts-flow.png)

## Getting Started

1. Download the parts from the [framework-base](framework-base) and [framework-prototypes](framework-prototypes) folders.
2. Open the parts in your favorite CAD software.
3. Modify the parts to fit your needs.
4. Print the parts using your 3D printer.
5. Assemble the parts using M3 nuts and bolts.
6. Share your project and prototypes with the community!
7. Have fun!

## Base Framework Parts

| Part (link)  | Image |
| --- | --- |
| [Platform](framework-base/platform.step)| <img src="docs/README/platform.png" width="200"> |
| [Bar - 1 Platform (left)](framework-base/bar-1p_left.step) | <img src="docs/README/bar-1p_left.png" width="200"> |
| [Bar - 1 Platform (right)](framework-base/bar-1p_right.step) | <img src="docs/README/bar-1p_right.png" width="200"> |
| [Bar - 2 Platforms](framework-base/bar-2p.step) | <img src="docs/README/bar-2p.png" width="200"> |
| [Bar - 3 Platforms](framework-base/bar-3p.step) | <img src="docs/README/bar-3p.png" width="200"> |
| [Shell - 22 mm](framework-base/shell-22.step) | <img src="docs/README/shell-22.png" width="200"> |
| [Shell - 34 mm](framework-base/shell-34.step) | <img src="docs/README/shell-34.png" width="200"> |
| [Shell - 46 mm](framework-base/shell-46.step) | <img src="docs/README/shell-46.png" width="200"> |
| [Lid](framework-base/lid.step) | <img src="docs/README/lid.png" width="200"> |

## Features

### Small Range of Parts

The framework is based on a small range of parts that can be easily combined to create a wide range of projects.

See: [Base Framework Parts](#base-framework-parts)

### Scalable

Choose the project of the size you need, and extend it in the future.

|     |     |     |
| --- | --- | --- |
| ![s1](docs/README/features/scalable-1.png) | ![s2](docs/README/features/scalable-2.png) | ![s3](docs/README/features/scalable-3.png) |


### Flexible

Adjust the project to your needs. Add or remove platforms, choose the right volume for your components.

|     |     |
| --- | --- |
| ![f1](docs/README/features/flexible-1.png) | ![f2](docs/README/features/flexible-2.png) |

### Easily Printable

All parts are designed for easy 3D printing. No supports are needed.

|     |     |     |
| --- | --- | --- |
| ![p1](docs/README/features/printable-1.png) | ![p2](docs/README/features/printable-2.png) | ![p3](docs/README/features/printable-3.png) |

### Rigid

The special shape of the bars makes the structure stable and rigid in all directions. The shells provide additional structural support.

![r1](docs/README/features/rigid.png)

### Modifiable

All parts are designed for easy modification. They are shipped in STEP format, which can be opened in any CAD software.

|     |     |     |
| --- | --- | --- |
| ![m1](docs/README/features/modifiable-1.png) | ➡️ | ![m2](docs/README/features/modifiable-2.png) |

|     |     |     |
| --- | --- | --- |
| ![m3](docs/README/features/modifiable-3.png) | ➡️ | ![m4](docs/README/features/modifiable-4.png) |

### Nuts as Inserts

The nuts are an accessible and reliable alternative to metal inserts, providing a strong and reusable connection between the parts.

|     |     |
| --- | --- |
| ![n1](docs/README/features/nuts-1.jpg) | ![n2](docs/README/features/nuts-2.jpg) |

### Modular

All the parts are made in the way so you don't have to re-print large volumes of plastic when you want to make a small change. Reprint only necessary parts.

|     |     |     |
| --- | --- | --- |
| ![mo1](docs/README/features/modular-0.jpg) | ![mo2](docs/README/features/modular-1.jpg) | ![mo3](docs/README/features/modular-2.jpg) |

## Prototypes

Prototypes are parts made on top of the base framework parts. They have some particular application in mind.

| Prototype (link) |  Application Recommendation | Image |
| ---              | ---      | ---   |
| [prototype-wheels-v2](framework-prototypes/prototype-wheels-v2/prototype-wheels-v2.step) | A rigid platform for two motorized wheels | <img src="framework-prototypes/prototype-wheels-v2/image.png" width="400"> |

## Example Projects

TBD

## Branding

The framework tries to keep the branding simple and consistent. The recommended colors are:

- Platforms: ![#57C6BD](https://via.placeholder.com/15/57C6BD/000000?text=+) `#57C6BD`
- Bars: ![#DD5228](https://via.placeholder.com/15/DD5228/000000?text=+) `#DD5228`
- Shells: ![#BCEFEA](https://via.placeholder.com/15/BCEFEA/000000?text=+) `#BCEFEA`
- Lids: ![#18948B](https://via.placeholder.com/15/18948B/000000?text=+) `#18948B`
- Prototypes: ![#DA5B5F](https://via.placeholder.com/15/DA5B5F/000000?text=+) `#DA5B5F`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
