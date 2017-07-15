# bfs-by-mapreduce
Use mapreduce approach to solve BFS problem<br/>
Example usecase from Frank Kane's Taming Big Data with MapReduce and Hadoop.<br/>
python pre_process_graph.py 5306 -- generate file for iteration<br/>
python bfs_iter.py --target=675 iter_0.txt >iter_1.txt -- first iteration<br/>
python bfs_iter.py --target=675 iter_1.txt >iter_2.txt -- second iteration<br/>
...
