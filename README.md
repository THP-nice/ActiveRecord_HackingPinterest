### Exercice HackingPinterest

Exercice réalisé dans le cadre de la semaine Rails (THP), par notre belle équipe :
- [Ysaline Macé](https://github.com/Ysalien)
- [Nikita Vasilev](https://github.com/nikitavasilev)
- [Arthur Mansuy](https://github.com/tutus06) 
- [Thomas Charvet](https://github.com/TomacTh) 
- [Nathaniel Debache](https://github.com/Natdenice).

### Database

HackingPinterest est une base de données, réalisée à partir de rails, dans laquelle les utilisateurs peuvent creer et acceder a des "pins". Ces pins incluent une url contenant une image. Les Utilisateurs de HackingPinterest peuvent commenter les pins mais ne peuvent pas commenter les commentaires. On retrouve ainsi trois models : Comment (table comments), User (table users) et Pin (table pins). Leur index est lié sur User et Pin.

##### NB
N'oubliez de faire un bundle install dans votre terminal ! Les models se trouvent dans le sous-fichier model, dans app. Les tables se trouvent dans le fichier migrate, contenu dans db.
