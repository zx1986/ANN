類神經網路

ann(輸入神經元[屬性]個數, 隱藏神經元個數, 輸出層神經元個數, [亂數種子]);

memalloc(*sizeof()):
	輸入神經元陣列 input[I]
	隱藏神經元陣列 hidden[H]

memalloc(*sizeof()):
	輸入層至隱藏層權重陣列 input_hidden[I][H]
	隱藏層至輸出層權重陣列 hidden_output[H][O]

input_hidden_init();
hidden_output_init();

hidden_sum();

hidden_output_update();
input_hidden_update();

data[row][I]
answer[row]
result[row]

# Tools

http://storm.apache.org
