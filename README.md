<!DOCTYPE html>
<html> 
<h1>Анкета для трудоустройства</h1>
    <form action="submit_form.php" method="post" enctype="multipart/form-data">
        <!-- Личные данные -->
        <label for="name">ФИО:</label>
        <input type="text" id="name" name="name" required placeholder="Введите ваше ФИО">
        <br><br>

        <label for="email">Электронная почта:</label>
        <input type="email" id="email" name="email" required placeholder="example@mail.com">
        <br><br>

        <label for="phone">Телефон:</label>
        <input type="tel" id="phone" name="phone" required placeholder="+7 (XXX) XXX-XX-XX">
        <br><br>

        <!-- Образование -->
        <label for="education">Уровень образования:</label>
        <select id="education" name="education" required>
            <option value="Среднее специальное">Среднее специальное</option>
            <option value="Высшее">Высшее</option>
           </select>
           <br><br>

        <!-- Опыт работы -->
        <label for="experience">Опыт работы:</label>
        <textarea id="experience" name="experience" rows="5" placeholder="Опишите ваш опыт работы"></textarea>
        <br><br>

        <label for="position">Желаемая должность:</label>
        <input type="text" id="position" name="position" placeholder="Введите желаемую должность">
        <br><br>
        <!-- Кнопка отправки -->
        <button type="submit">Отправить анкету</button>
    </form>
 <footer>
        <p>Сайт для трудоустройства 2024</p>
    </footer>
</body>
</html>

