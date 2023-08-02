Pipe Overview
#############

Layout Styles
*************

.. image:: ../_images/pipe_layout_types.gif
        :width: 650px

The :class:`NodeGraphPySide6.NodeGraph` class has 3 different pipe layout styles as
shown above this can be set easily with the :meth:`NodeGraphPySide6.NodeGraph.set_pipe_style`
function.

|
| Here's a example snippet for setting the pipe layout style to be "angled".

.. code-block:: python
    :linenos:

    from NodeGraphPySide6 import NodeGraph
    from NodeGraphPySide6.constants import PipeLayoutEnum

    graph = NodeGraph()
    graph.set_pipe_style(PipeLayoutEnum.ANGLE.value)

| There are 3 different pipe layout styles see: :attr:`NodeGraphPySide6.constants.PipeLayoutEnum`

.. note::

    If you've set up your node graph with the :meth:`NodeGraph.set_context_menu_from_file`
    function and the example
    `example JSON <https://github.com/jchanvfx/NodeGraphPySide6/blob/master/examples/hotkeys/hotkeys.json>`_
    then you'll already have the actions to set the pipe layout under the
    "Pipes" menu.

    .. image:: ../_images/pipe_layout_menu.png


Layout Direction
****************

The :class:`NodeGraphPySide6.NodeGraph` pipes can also be set with a vertical layout
direction with the  :meth:`NodeGraphPySide6.NodeGraph.set_layout_direction` function.

.. image:: ../_images/vertical_layout.png
