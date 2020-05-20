from enum import Enum

TOKEN = ""
db_file = "database.vdb"
user_choice = 0


class States(Enum):
    S_START = "0"
    S_CHOOSE_BTN = "1"
    S_ENTER_VALUE = "2"
    S_BACK = "3"


button_captions = {
    1: "USD-UAH",
    2: "EUR-UAH",
    3: "UAH-USD",
    4: "UAH-EUR",
    5: "Back",
}

reply_messages = {
    1: "USD-UAH",
    2: "EUR-UAH",
    3: "UAH-USD",
    4: "UAH-EUR",
}

hello_message = """Здравствуйте! Здесь Вы можете перевести UAH в USD или EUR, и наоборот. Используйте кнопки ниже)"""
choose_btn = """Выберите пожалуйста кнопку еще раз"""
for_exchange_message = """Введите сумму для перевода """
after_exchange_message = """Вы выполнили перевод: """
error_message = """Произошла ошибка, попробуйте еще раз"""
back_message = """Вы вернулись в основное меню"""
back__message = """Чтобы использовать бота снова - нужно вернуться в основное меню"""
