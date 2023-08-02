:hide-rtoc:

Port Nodes
##########

| Port nodes are the nodes in a expanded :class:`NodeGraphPySide6.SubGraph` that
  represent the ports from the parent :class:`NodeGraphPySide6.GroupNode` object.

**Classes:**

.. autosummary::
    NodeGraphPySide6.nodes.port_node.PortInputNode
    NodeGraphPySide6.nodes.port_node.PortOutputNode

----

.. hint::

    Port node objects can be accessed in a expanded
    :class:`NodeGraphPySide6.GroupNode` with:

    - :meth:`NodeGraphPySide6.SubGraph.get_node_by_port`,
    - :meth:`NodeGraphPySide6.SubGraph.get_input_port_nodes`,
    - :meth:`NodeGraphPySide6.SubGraph.get_output_port_nodes`

|

PortInputNode
=============

.. autoclass:: NodeGraphPySide6.nodes.port_node.PortInputNode
    :members:
    :member-order: bysource
    :exclude-members: NODE_NAME

|

PortOutputNode
==============

.. autoclass:: NodeGraphPySide6.nodes.port_node.PortOutputNode
    :members:
    :member-order: bysource
    :exclude-members: NODE_NAME
