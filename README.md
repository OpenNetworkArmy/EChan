# EChan
This is a Solidity contract for an imageboard where users can post messages in threads on various boards. The contract stores the messages in a data structure called a mapping, which is a type of associative array that can store key-value pairs. The key is a string representing the board name, the value is a nested mapping where the key is a string representing the thread name and the value is an array of strings representing the posts in the thread.

The contract has two functions: post and view_Thread. The post function allows users to post a message to a specified board and thread. It takes three arguments: p_Board, p_Thread, and p_Post, which represent the board, thread, and message respectively. The function stores the message in the appropriate location in the mapping.

The view_Thread function allows users to view a range of messages in a particular thread. It takes four arguments: p_Board, p_Thread, p_Post, and p_Count, which represent the board, thread, starting message number, and number of messages to view respectively. The function checks to make sure the number of messages specified actually exist, and if not, it adjusts the count accordingly. It then retrieves the specified messages from the mapping and returns them in an array.

Deployed at: https://etherscan.io/address/0x349464a482168e1f00b3b53e04188c8f96755a4b

We built no fees into it, no royalties, we get nothing from its use. Not financially anyway, providing a censorship free platform does bring us good feels.
