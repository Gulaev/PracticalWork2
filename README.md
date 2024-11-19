For test

1

1> lesson3_task1:first_word(<<"Hello World">>).

Result

<<"Hello">>.

2

2> lesson3_task2:words(<<"Hello World from Erlang">>).

Result

[<<"Hello">>, <<"World">>, <<"from">>, <<"Erlang">>].


3

3> lesson3_task3:split(<<"a,b,c,d">>, <<",">>).

Result

[<<"a">>, <<"b">>, <<"c">>, <<"d">>].


4

JsonObject = <<"{\"key1\": \"value1\", \"key2\": \"value2\"}">>.

4> lesson3_task4:decode(JsonObject, proplist).

Result

[{<<"key1">>,<<"value1">>},{<<"key2">>,<<"value2">>}]
