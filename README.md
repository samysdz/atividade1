Relatório jogo:

1) Peguei a base do jogo asteroids.

2) Modifiquei o formato da nave em ship.cpp

3) Modifiquei as cores dos asteroids em asteroids.cpp no "asteroid.m_color = glm::vec4(0,1,0,1) * randomIntensity(re);"

4) Modifiquei o tom de cor da nave em ship.cpp no "glm::vec4 m_color{0.3};"

5) Modifiquei a quantidade de lados dos ateroids em asteroids.cpp no "std::uniform_int_distribution<int> randomSides(3, 7);"

6) Modifiquei a velocidade dos asteroids quando quebrados em asteroids.cpp no "asteroid.m_velocity = glm::normalize(direction) / 3.0f;"


