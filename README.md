# nec4uHka-Ha-koHBeuepe
песчинка на конвейере, mingw32

По теме https://www.youtube.com/watch?v=RPj2Eu3D00Y .

Песчинка единственная , сразу прилипает при контакте, связь с конвейером через пружину kx и диссипацию проп.скорости деформации по модулю, проскальзывания нет. КПД по затрате кинетической энергии конвейера после успокоения колебаний.

С упругостью и небольшой диссипацией потеря энергии не большая. У меня по численным расчётам получилось КПД около 99.9. Диссипация в СИ пропорционально модулю скорости деформации с к=0.0001.  жёсткость_натяжения_ко_СИ=1.0/1e-3; масса конвейера 100кг, масса_песчинки_кг = 0.1;

Компилируется GCC, mingw32 из комплекта msys2.
