# Rin 3D Test — Android

Protótipo 3D nativo para Android, sem assets externos e sem bibliotecas de jogo.

## Conteúdo
- Campo 3D e gol
- Goleiro com IA simples: acompanha a trajetória da bola e tenta interceptar
- Rin controlável por joystick virtual
- Bola física simplificada
- 3 skills:
  1. Curve Shot — chute curvado
  2. Destructive Dribbles — aumento temporário de velocidade
  3. Impulsive Dash — arrancada rápida
- Placar de gols
- Orientação horizontal

## Compilar no Android Studio
1. Abra a pasta `Rin3DTest`.
2. Aguarde o Gradle sincronizar.
3. `Build > Build APK(s)`.
4. O APK de debug ficará em `app/build/outputs/apk/debug/app-debug.apk`.

O ambiente usado para gerar este projeto não possui Android SDK/Gradle instalados, então o APK binário não pôde ser compilado aqui.
