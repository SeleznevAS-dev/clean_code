# Урок 4 - Имена, которых следует избегать

total_amount - amount_total // постфикс в конце

max_possible - possible_max // постфикс в конце (частая ошибка у меня)

cycles - num_cycles // количество циклов работы программы (неинформативное имя)

src_list - script_tags_src_list // неинформативное имя

timestamp - milliseconds_timestamp // не хватает суффикса, единицы измерения

log - withdraw_tx_receipt_logs // неинформативное имя

storage_hash - storage_hash_hex // не хватает суффикса, что именно в hex формате

result - response // много где в коде в качестве ответа на api запрос используется result вместо response (относится к пункту 3)

result - result_string // окей, result вообще часто слишком много что означает, так точно не должно быть

current_value - element_value // значение атрибута value у элемента, изначально неинформативное имя

idx - random_index // неинформативное имя, тут имелся в виду именно рандомный индекс

url - tg_api_send_message_url // частовстречающееся неинформативное имя длиной меньше 8 символов