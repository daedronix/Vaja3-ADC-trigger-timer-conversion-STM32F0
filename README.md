# Vaja3-ADC-trigger-timer-conversion-STM32F0
<h4> Glede na vašo razvojno ploščo in razširitveno vezje s tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? </h4>
<p> To je pin PC0. </p>
<h4> Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? </h4>
<p> Poleg pina se izpiše ADC_IN10 </p>
<h4> Aktiviramo samo zeleno LED diodo na ustreznem izhodu. </h4>
<p> Aktiviramo samo pin PC9. </p>
<h4> V "Clock configuration" spremenimo APB1 Timer clock (MHz) na 16 MHz. Kaj opazite? </h4>
<p> Opazimo, da se vrednosti spremenijo na isto vrednost kot APB1 Timer Clock </p>
<h4> V "Configuration" kliknemo gumb za TIM1, ki je v polju "Control". Časovniku bi radi spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju "Prescaler" (PSC-16 bit value). Koliko znaša ta vrednost? </h4>
<p> Vrednost je 16000. </p>
<h4> Branje vrednosti želimo prikazati z utripanjem zelene LED diode na STM32F0 ploščici. Uporabite metodo "TogglePin" iz HAL knjižnice in zapišite ukaz. </h4>
<p> HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9); </p>
