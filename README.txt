Instance file format
------------------------------------------------------------------------------------------

			VERTEX_COUNT <number_of_vertices>
			PATH_COUNT <number_of_paths>
			BUDGET <available_budget>
			<------------ VERTICES ------------>
			<vertex_id>;<vertex_title>;<latitude>;<longitude>;<cost>;<score>
			...
			...
			...
			<------------- EDGES -------------->
			<edge_id>;<vertex_A>;<vertex_B>;<cost>;<score>
			...
			...
			...

Solution file format
------------------------------------------------------------------------------------------

			<name_of_the_instance>;<best_score>;<cpu_time>
			...

Solution file details format
------------------------------------------------------------------------------------------

			Instance <name_of_the_instance>
			CPU time = <cpu_time> sec
			Total score = <best_score>
			Total consumed budget = <consumed_budget>
			start_vertex_id --(edge_1_id)--> vertex_1_id --(edge_2_id)--> ...  vertex_n_id --(edge_n_id)--> destination_vertex_id
			...
			...
			...