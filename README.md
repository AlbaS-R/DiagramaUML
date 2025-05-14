# 📏 Normas para actualizar el UML
🔁 Siempre que se modifiquen clases, métodos o relaciones, el diagrama UML debe actualizarse.

Mantén sincronizados el código y el archivo diagrama.puml.

Usa composición (*--) cuando una clase depende fuertemente de otra.

Usa herencia (<|--) si una clase extiende a otra.

El UML debe estar en docs/uml/diagrama.puml.


# 🛠 Ciclo de desarrollo recomendado
Diseño UML
Diseña nuevas clases o métodos en diagrama.puml.

Implementación en código
Crea o modifica clases en /src.

Actualización del UML
Si cambiaste el diseño durante la implementación, actualiza el UML.

Commit:

git add src/ docs/uml/diagrama.puml
git commit -m "feat: implementar clase AgenteSoporte y actualizar UML"
git push

# 👀 Cómo ver el UML en VS Code
Instala la extensión PlantUML desde el Marketplace.

Asegúrate de tener Java instalado.

Abre el archivo .puml → clic derecho → Preview Current Diagram o usa Alt + D.


# 🤝 Contribución
Si deseas contribuir:

Crea un branch con tu cambio: git checkout -b feat/nombre-clase.

Haz cambios en código y UML.

Asegúrate de que el diagrama refleja el nuevo estado.

Haz un pull request con descripción clara de tus cambios.

¡Gracias por mantener el proyecto limpio, sincronizado y bien documentado! 🎮

