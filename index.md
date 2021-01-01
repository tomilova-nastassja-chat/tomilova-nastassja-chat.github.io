<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Учебная страница</title>
	</head>

	<body>
		<script>
			var pickRandomWord = function(words) {
				return words[Math.floor(Math.random() * words.length)].toLowerCase();
			};

			var generateRandomInsult = function(){
			var randomBodyParts = [
				"Голова",
				"Шея",
				"Мозга",
				"Пятка"
			];
			

			var randomAdjectives = [
				"Вонючая",
				"Унылая",
				"Дурацкая",
				"Тупая"
			];

			var randomWords = [
				"Муха",
				"Выдра",
				"Дубина"
			];

			return "Твоя " + pickRandomWord(randomBodyParts) + " словно " + pickRandomWord(randomAdjectives) + " " + pickRandomWord(randomWords) + "!!!";
		};
		</script>
	</body>
</html>
