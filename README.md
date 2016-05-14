# PhD Thesis: Resonant Pulse Propagation in Dense Atomic Vapours

- Thomas P. Ogden
- Department of Physics, Durham University

## Latest Release

- https://github.com/tommyogden/phd-thesis/releases/download/v1.0/thesis.pdf (10MB)

## Abstract

  This thesis presents theoretical models and results of numerical simulations
  describing the propagation of optical pulses through dense, thermal atomic
  vapours. In particular we investigate the nonlinear effects of optical
  solitons due to self-induced transparency (SIT) in two-level systems,
  optical simultons in V-type three-level systems and electromagnetically
  induced transparency (EIT) in Λ-type systems, including the
  storage and retrieval of dark-state polaritons.

  An investigation is made into two-photon excitation of the 5D states of
  rubidium in a high-intensity beam including the hyperfine structure of the
  relevant atomic levels. Decay from these states to the 6P manifolds is ruled
  out as a cause of experimentally observed fluorescence due to the amount of
  power broadening associated with intensities necessary to provide any
  significant level of population in these highly excited states.

  We combine the nonlinear effects of optical solitons and EIT to
  explain experimentally observed steepened pulses in a V-type system in a
  micron-length cell. We explain the behaviour as the early formation of a
  simulton pulse drawn from a CW probe field by a strong coupling
  pulse, due to coherent population trapping. We predict that in a longer cell
  it may be possible to facilitate propagation of matched pulses, even when the
  transitions in the system have different propagation coefficients, as long as
  decoherence from collision broadening can be controlled. The fact that weak
  pulses can propagate with this scheme suggests an approach to achieving
  transparent propagation of single or few photon pulses distinct from, but
  related to, both SIT and EIT.

## How do I make this a PDF?

To produce a PDF document from this TeX source, and run the following commands.
(You need to have a TeX implementation installed.)

```bash
cd thesis         # Move to the thesis/ subdirectory
pdflatex thesis   # Convert the TeX source to a PDF document
bibtex thesis     # Produce the reference list
pdflatex thesis   # Render the reference list
pdflatex thesis   # Once more for luck
```

## Copyright

Copyright 2016 Thomas P. Ogden.

The copyright of this thesis rests with the author. No quotation
from it should be published without their prior written consent and
information derived from it should be acknowledged.
