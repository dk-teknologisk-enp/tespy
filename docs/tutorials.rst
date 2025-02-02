.. _tespy_tutorial_label:

~~~~~~~~~~~~~~~~~~
Advanced Tutorials
~~~~~~~~~~~~~~~~~~
We provide more advanced tutorials for you to better understand how to work
with more complex systems in TESPy.

At the example of different heat pump topologies, you will learn to

- create a more complex model *step by step* and get the idea of designing a
  plant and calculating the offdesign behavior.
- set up a code structure, which allows you to generate stable starting values
  flexibly, helping you to build reliable setups faster.
- use the inbuilt exergy analysis method in a simple geothermal heat pump
  setting.

Furthermore, we introduce the coupling of TESPy with pygmo in order to create
an optimization problem, which optimizes thermal efficiency of a clausius
rankine power plant. Another typical setup are heat recovery steam generators
using exhaust gases from an open cycle gas turbine.

Finally, we provide an approach on how to model complex district heating
systems. If you have any questions, ideas for other tutorials or feedback,
please reach out to us. We are looking forward to hearing from you!

.. grid:: 2
    :gutter: 1

    .. grid-item-card::  Build complex systems step by step
        :link: tespy_tutorial_heat_pump_label
        :link-type: ref

        .. image:: /_static/images/tutorials/heat_pump_stepwise/flowsheet.svg
            :class: only-light

        .. image:: /_static/images/tutorials/heat_pump_stepwise/flowsheet_darkmode.svg
            :class: only-dark

    .. grid-item-card::  Generate stable starting values
        :link: tespy_tutorial_starting_values_label
        :link-type: ref

        .. image:: /_static/images/tutorials/heat_pump_starting_values/COP_by_wf.svg
            :class: only-light

        .. image:: /_static/images/tutorials/heat_pump_starting_values/COP_by_wf_darkmode.svg
            :class: only-dark

.. grid:: 2
    :gutter: 1

    .. grid-item-card::  Exergy analysis of a heat pump
        :link: tespy_tutorial_heat_pump_exergy_label
        :link-type: ref

        .. image:: /_static/images/tutorials/heat_pump_exergy/diagram_E_D.svg
            :class: only-light

        .. image:: /_static/images/tutorials/heat_pump_exergy/diagram_E_D_darkmode.svg
            :class: only-dark

    .. grid-item-card::  Building Complex District Heating Systems

        Coming soon!

.. grid:: 2
    :gutter: 1

    .. grid-item-card::  Optimization of a thermal power plant
        :link: tespy_tutorial_pygmo_optimization_label
        :link-type: ref

        .. image:: /_static/images/tutorials/pygmo_optimization/pygmo_optimization.svg
            :class: only-light

        .. image:: /_static/images/tutorials/pygmo_optimization/pygmo_optimization_darkmode.svg
            :class: only-dark

    .. grid-item-card::  Gas Turbine with Heat Recovery Steam Generator

        Coming soon!


.. toctree::
    :maxdepth: 1
    :glob:
    :hidden:

    tutorials/heat_pump_steps.rst
    tutorials/starting_values.rst
    tutorials/heat_pump_exergy.rst
    tutorials/pygmo_optimization.rst
