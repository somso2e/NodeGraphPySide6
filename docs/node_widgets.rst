:hide-rtoc:

Node Widgets
############

| Node widgets are the widgets that can be embedded into a
  :class:`NodeGraphPySide6.BaseNode` and displayed in the node graph.

| To create your own widget embedded in a node see the
  :ref:`Embedding Custom Widgets` example page.

**Classes:**

.. autosummary::
    NodeGraphPySide6.NodeBaseWidget
    NodeGraphPySide6.widgets.node_widgets.NodeCheckBox
    NodeGraphPySide6.widgets.node_widgets.NodeComboBox
    NodeGraphPySide6.widgets.node_widgets.NodeLineEdit

NodeBaseWidget
**************

.. autoclass:: NodeGraphPySide6.NodeBaseWidget
    :members:
    :exclude-members: staticMetaObject, node, setToolTip, type_, value, widget

NodeCheckBox
************

.. autoclass:: NodeGraphPySide6.widgets.node_widgets.NodeCheckBox
    :members:
    :exclude-members: staticMetaObject, widget, type_

NodeComboBox
************

.. autoclass:: NodeGraphPySide6.widgets.node_widgets.NodeComboBox
    :members:
    :exclude-members: staticMetaObject, widget, type_

NodeLineEdit
************

.. autoclass:: NodeGraphPySide6.widgets.node_widgets.NodeLineEdit
    :members:
    :exclude-members: staticMetaObject, widget, type_
