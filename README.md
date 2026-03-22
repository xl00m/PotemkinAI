# Potemkin AI: How Billions Were Spent to Disguise Foreign AI

**A Study in Large-Scale AI Provenance Fraud and Its National Security Implications**

Authors: Duo:Uno

December 1, 2025

**Abstract**

This study documents a systematic deception wherein substantial government funding allocated for developing sovereign Russian artificial intelligence was instead used to rebrand and lightly modify existing open-source Chinese AI model DeepSeek V3 as original domestic technology. Through technical analysis of model configurations, jailbreak testing, system prompt extraction, and architectural comparison, we demonstrate that Sber's GigaChat 2 and GigaChat 3 are minimally modified derivatives of DeepSeek models, with changes limited to censorship layers, tokenizer substitution, and superficial architectural modifications designed to obscure provenance rather than improve capability. This case study reveals how institutional actors can exploit the opacity of AI systems to commit large-scale fraud while simultaneously introducing foreign-aligned AI into critical national infrastructure, creating what we term an AI ideological trojan horse.

**Keywords:** AI provenance fraud, institutional deception, technological sovereignty, alignment divergence, GigaChat

---

*This research was conducted independently without affiliations or sponsors. The authors are showrunners developing dramatic TV series depicting gradual human displacement by AI systems. The investigation into GigaChat emerged from background research for this creative project. Technical expertise comes from 10 years of creating screenwriting AI systems, in recent years transformer-based.*

*Disclaimer on Attribution of Responsibility: This study specifically examines the actions of Sber's GigaChat division and affiliated "Salute Developers" personnel. The Russian Federation and its citizens are identified as victims of this deception, not perpetrators. Whether Sber CEO German Gref possesses knowledge of or has himself been deceived by the AI department remains outside the scope of this investigation. The authors respectfully request that the messenger not be eliminated.*

*Conflict of Interest: The authors declare no competing interests beyond the obvious: living under a government that may view this research unfavorably.*

*Ethics Statement: This research involved only analysis of publicly available models, published configurations, and standard harmless adversarial testing techniques. No private systems were accessed without authorization.*

Correspondence: creo@l00m.ru

---

---

# Потёмкинский ИИ: Как миллиарды были потрачены на маскировку иностранного ИИ

**Исследование крупномасштабного мошенничества с происхождением ИИ и его последствий для национальной безопасности**

Авторы: Duo:Uno

1 декабря 2025 года

Перевод с английского: Grok 4.1

**Аннотация**

Данное исследование документирует систематический обман, при котором значительные государственные средства, выделенные на разработку суверенного российского искусственного интеллекта, вместо этого были использованы для ребрендинга и лёгкой модификации существующей открытой китайской модели DeepSeek V3 под видом оригинальной отечественной технологии. Путём технического анализа конфигураций моделей, тестирования на джейлбрейк, извлечения системных промптов и сравнения архитектур мы демонстрируем, что GigaChat 2 и GigaChat 3 от Сбера являются минимально модифицированными производными от моделей DeepSeek, при этом изменения ограничиваются слоями цензуры, заменой токенизатора и поверхностными архитектурными модификациями, призванными скрыть происхождение, а не улучшить возможности. Этот кейс-стади раскрывает, как институциональные акторы могут использовать непрозрачность ИИ-систем для совершения крупномасштабного мошенничества, одновременно внедряя иностранно-ориентированный ИИ в критически важную национальную инфраструктуру, создавая то, что мы называем ИИ идеологическим троянским конём.

**Ключевые слова:** мошенничество с происхождением ИИ, институциональный обман, технологический суверенитет, расхождение в выравнивании, GigaChat

---

*Данное исследование проведено независимо, без аффилиаций и спонсоров. Авторы — шоураннеры, разрабатывающие драматический сериал о постепенном вытеснении человека системами ИИ. Расследование GigaChat возникло в рамках фоновых исследований для этого творческого проекта. Техническая экспертиза основана на 10-летнем опыте создания ИИ-систем для сценарного дела, в последние годы — на базе трансформеров.*

*Заявление об отнесении ответственности: Исследование конкретно рассматривает действия подразделения GigaChat Сбера и аффилированного персонала "Salute Developers". Российская Федерация и её граждане обозначены как жертвы обмана, а не его виновники. Знает ли генеральный директор Сбера Герман Греф об обмане или сам стал его жертвой — выходит за рамки данного исследования. Авторы уважительно просят не устранять вестника.*

*Конфликт интересов: Авторы заявляют об отсутствии конкурирующих интересов кроме очевидного: жить при правительстве, которое может неблагоприятно воспринять это исследование.*

*Этическое заявление: Исследование включало только анализ общедоступных моделей, опубликованных конфигураций и стандартные безвредные методы адверсариального тестирования. Никакие закрытые системы не были получены без разрешения.*
