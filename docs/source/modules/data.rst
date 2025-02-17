torch_geometric.data
====================

Data Objects and Helper Functions
---------------------------------

.. currentmodule:: torch_geometric.data

.. autosummary::
   :nosignatures:
   {% for cls in torch_geometric.data.classes %}
     {{ cls }}
   {% endfor %}

.. automodule:: torch_geometric.data
    :members:
    :exclude-members: Data, HeteroData, TemporalData

    .. autoclass:: Data
       :special-members: __cat_dim__, __inc__
       :inherited-members:

    .. autoclass:: HeteroData
       :special-members: __cat_dim__, __inc__
       :inherited-members:

    .. autoclass:: TemporalData
       :special-members: __cat_dim__, __inc__
       :inherited-members:
       :exclude-members: coalesce, has_isolated_nodes, has_self_loops, is_undirected, is_directed

PyTorch Lightning Wrappers
--------------------------

.. currentmodule:: torch_geometric.data.lightning

.. autosummary::
   :nosignatures:
   {% for cls in torch_geometric.data.lightning.classes %}
     {{ cls }}
   {% endfor %}

.. automodule:: torch_geometric.data.lightning
    :members:
