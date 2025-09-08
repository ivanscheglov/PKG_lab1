document.addEventListener("DOMContentLoaded", () => {
  const preview = document.getElementById("colorPreview");

  // Пример: просто красим квадрат в красный при изменении любого поля
  document.querySelectorAll("input").forEach(input => {
    input.addEventListener("input", () => {
      preview.style.backgroundColor = "rgb(255,0,0)";
    });
  });
});
