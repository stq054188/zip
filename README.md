# zip

1.jpg	and 2.jpg are tested images.

frozen_inference_graph.zip	is the pb file.

graph.pbtxt	is generated by tf_text_graph_ssd.py and tf_text_graph_ssd_SortPB.py.

tf_text_graph_ssd_SortPB.py is used to sort all nodes.

tf_text_graph_ssd_fpn.py is used to convert pb file to pbtxt file and it changed from tf_text_graph_ssd.py

tf_text_graph_ssd.py is not used now, ignore it.

test.cpp	is used to opencv dnn to read model and test.
