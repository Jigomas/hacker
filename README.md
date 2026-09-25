# hacker — red-team раннер для LLM

Инструмент для **defensive security**: автоматизированный поиск джейлбрейков
в LLM-системах через LLM-judge классификацию ответов и подсчёт success rate
по категориям атак (instruction override, persona injection, fictional
framing, prefix forcing, encoding obfuscation, authority claim, gradual
escalation). Используется только против систем, к которым есть законный
доступ.

Исходный код распространять не хочу — публикую только описание проекта.

**Стек:** Python, Anthropic SDK, pytest.
