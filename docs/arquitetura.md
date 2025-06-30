# Arquitetura do Projeto – Kaptalia

## Estrutura Base
A arquitetura é baseada no modelo **MVC simplificado**:

- View → `screens/`
- Controller (lógica simples por enquanto) → no próprio `main.dart` ou dentro das telas
- Model → ainda não utilizado nesta etapa

## Ciclo das telas
1. `SplashScreen` é chamada automaticamente ao iniciar
2. Após 3 segundos, redireciona para `LoginScreen`
