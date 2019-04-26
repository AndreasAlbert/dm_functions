# dm_functions
Utility functions to deal with DM interpretations.

## DMSimp mediator widths
Individual functions exist for partial widths, and the total width of axial-vector, vector, scalar and pseudoscalar mediators.

Let's calculate the total mediator width for an axial mediator:

```python
from dmsimp.mediator_width import gamma_axial_total

width = gamma_axial_total(m_med = 1000, # GeV \
                          m_x = 1, # GeV \
                          g_q = 0.25, \
                          g_chi = 1.0, \
                          g_l=0)
```

To get partial widths or other mediator types, just check out the full list of functions:
* [gamma_axial_lepton](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L44)
* [gamma_axial_neutrino](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L60)
* [gamma_axial_quark](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L71)
* [gamma_axial_chi](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L87)
* [gamma_axial_total](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L104)
* [gamma_vector_lepton](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L127)
* [gamma_vector_neutrino](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L143)
* [gamma_vector_quark](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L154)
* [gamma_vector_chi](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L170)
* [gamma_vector_total](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L187)
* [gamma_pseudo_chi](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L209)
* [gamma_pseudo_quark](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L225)
* [gamma_pseudo_gluon](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L242)
* [gamma_pseudo_total](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L257)
* [gamma_scalar_chi](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L276)
* [gamma_scalar_quark](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L292)
* [gamma_scalar_gluon](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L309)
* [gamma_scalar_total](https://github.com/AndreasAlbert/dm_functions/blob/master/dmsimp/mediator_width.py#L324)


                      
