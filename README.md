# Turtle.pas

A lightweight turtle graphics library for Delphi (FireMonkey / FMX), inspired by Python’s `turtle` module.

It provides a `TTurtleScreen` you attach to a `TPaintBox`, and a `TTurtle` that executes familiar commands like `forward`, `left/right`, `circle`, `begin_fill/end_fill`, `pencolor`, `pensize`, plus simple animation controls.

## Features

- Easy-to-use API: `forward`, `backward`, `left/right`, `goto`, `home`, `circle`, `dot`, `stamp`, `write`
- Pen + fill support: `pencolor`, `pensize`, `fillcolor`, `begin_fill`, `end_fill`
- Animation control: `tracer(N, delay)`, `update()`, `no_animation(...)`
- Shape system: built-in shapes + `register_shape(...)` for polygons or images
- Basic input events: click and key handlers (FMX-style)
