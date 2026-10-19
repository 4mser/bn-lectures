<p align="center">
  <img src="docs/assets/hero.gif" width="100%" alt="Four moments from the B&N Lectures teaser in 16:9: a black hole with its accretion disk, a cream and violet Julia fractal, a DNA helix made of turquoise particles, and the B&N LECTURES mark between two charges over the field lines">
</p>

<p align="center">
  <a href="https://bnsolutions.cl/lectures"><b>bnsolutions.cl/lectures</b></a> &nbsp;·&nbsp;
  <!-- TODO: replace with the YouTube channel link once it is live -->
  <a href="TODO-canal-youtube"><b>YouTube channel</b></a> &nbsp;·&nbsp;
  <a href="https://bnsolutions.cl"><b>B&N Solutions</b></a> &nbsp;·&nbsp;
  <a href="README.md">Leer en español</a>
</p>

B&N Lectures are animated lessons in mathematics, physics, computing, chaos and geometry, made by B&N Solutions. Every video is programmed end to end: scenes are functions of time, simulations solve the actual physics, and every number on screen is computed in the same frame. The lessons are in Spanish.

All the code is open. This repository is the starting point: it explains the project and links to the three repositories where each part lives.

### `// 01` The repositories

<table>
  <tr>
    <td width="33%" valign="top"><a href="https://github.com/4mser/bn-lectures-clases"><img src="docs/assets/card-clases.gif" width="100%" alt="Six moments from the Electricity and Magnetism series: Rutherford, the torsion balance, the field lines of a dipole, a charge on a parabolic path, the infinite plane and a charged semicircle"></a><br><a href="https://github.com/4mser/bn-lectures-clases"><b>bn-lectures-clases</b></a><br><sub>The lessons, organized by degree and course. It starts with the six Electricity and Magnetism lessons, the notes they follow and the template for new lessons.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/4mser/bn-lectures-teaser"><img src="docs/assets/card-teaser.gif" width="100%" alt="Black hole with a white accretion disk bending above and below the shadow"></a><br><a href="https://github.com/4mser/bn-lectures-teaser"><b>bn-lectures-teaser</b></a><br><sub>The 93-second teaser in 4:5, 16:9 and 9:16: a canvas and WebGL2 engine, precomputed simulations and every cut anchored to the song.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/4mser/bn-lectures-biblioteca"><img src="docs/assets/card-biblioteca.gif" width="100%" alt="Mosaic of simulation thumbnails changing one by one: electric fields, a black hole, reaction-diffusion and orbits"></a><br><a href="https://github.com/4mser/bn-lectures-biblioteca"><b>bn-lectures-biblioteca</b></a><br><sub>The catalog of the 192 simulations and effects from B&N's videos, with their equation, their origin and seven modules ready to reuse.</sub></td>
  </tr>
</table>

### `// 02` How a lesson is made

| | |
|---|---|
| **The script drives it** | Each lesson starts from a script written sentence by sentence. The voice is generated from that text and returns the exact time of every word; animations are anchored to those words, so when the script changes the lesson re-times itself. |
| **Physics computed in the frame** | Field lines are integrated, forces are summed and constants come from CODATA. What you see is the result of the calculation, not an approximate drawing. |
| **Three formats, one lesson** | `Clase` (4:5), `ClaseYT` (16:9) and `ClaseTT` (9:16) share scenes, voice and timing. Only the layout of each frame changes. |
| **Based on real course notes** | The Electricity and Magnetism series follows Javier Patiño's notes and derivations section by section, and is published alongside them. |
| **Reproducible** | Every frame is a function of time. Any frame can be rendered on its own, in any order and in parallel, and it comes out the same. |

### `// 03` The Electricity and Magnetism series

Six lessons in order, from electric charge to continuous distributions.

| # | Lesson | What it covers | Video |
|---|---|---|---|
| 1 | [Del ámbar a la carga elemental](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/01-del-ambar-a-la-carga-elemental) | The history of charge, from Thales to Millikan | `TODO` |
| 2 | [La ley de Coulomb](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/02-la-ley-de-coulomb) | The torsion balance, the law and superposition | `TODO` |
| 3 | [El campo eléctrico y sus líneas](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/03-el-campo-electrico-y-sus-lineas) | From action at a distance to Faraday's lines | `TODO` |
| 4 | [Una carga en un campo](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/04-una-carga-en-un-campo) | A free charge in a uniform field, compared with free fall | `TODO` |
| 5 | [De lo discreto a lo continuo](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/05-de-lo-discreto-a-lo-continuo) | The six classic field derivations | `TODO` |
| 6 | [Densidades no uniformes](https://github.com/4mser/bn-lectures-clases/tree/main/clases/fisica/electricidad-y-magnetismo/06-densidades-no-uniformes) | Two guided exercises with a varying density | `TODO` |

### `// 04` Team

B&N Lectures is made by three people.

**Nicolás Moreno** · [@4mser](https://github.com/4mser) · [LinkedIn](https://www.linkedin.com/in/nicolasmorenoavila)<br>
Creative and technical director of B&N Lectures. He designed and programmed:

- the animation engine (canvas and WebGL2 scenes, the retro look and the kinetic typography);
- the system that syncs every frame to the music: audio analysis, beat conform and the song's real events;
- the physics simulators: 2D Schrödinger, fluids, Gray-Scott, field LIC, Chladni and Lorenz on the GPU;
- the teaser in its three formats;
- the series of animated Electricity and Magnetism lessons;
- the library of 192 simulations and the template for new lessons.

**Benjamín Campos** · [@B3njjaman](https://github.com/B3njjaman)<br>
Co-founder of B&N Solutions. He made the original reel «De lo discreto a lo continuo» and the simulation engine the series builds on.

**Javier Patiño**<br>
Physics graduate and lecturer. Author of the Electricity and Magnetism notes and derivations the lessons are based on, and the voice of B&N Lectures.

### `// 05` License

The code and documentation in all four repositories are under the [MIT License](LICENSE), © 2026 B&N Solutions.

The B&N Solutions name, the B&N mark and logo and the name «B&N Lectures» are not covered by MIT and remain with B&N Solutions ([TRADEMARKS.md](TRADEMARKS.md)). Javier Patiño's notes and derivations carry their own license, stated in their folder in `bn-lectures-clases`. The teaser's music is not redistributed.

---

<p align="center">
  <img src="docs/assets/footer.svg" width="100%" alt="Field lines of a dipole flowing between two charges, with the text cuadro = f(t) and bnsolutions.cl/lectures">
</p>
