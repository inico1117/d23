# d23

>> plot(cos(0:pi/20:2*pi));
>> hold on
>> plot(sin(0:pi/20:2*pi));
>> x = 0:pi/20:2*pi;
>> plot(x,sin(x));
>> hold off
>> x = 0:pi/20:2*pi;
>> plot(x,sin(x));

>> plot(sin(0:pi/20:2*pi),'om--');
>> hold on
>> plot(cos(0:pi/20:2*pi),'xg:');
>> hold off

>> x = 0:0.5:4*pi;
>> y = sin(x);
>> h = cos(x);
>> w = 1./(1+exp(-x));
>> g = 1/((2*pi*2)^0.5).*exp((-1.*(x-2*pi).^2)./(2*2^2));
>> plot(x,y,'bd-',x,h,'gp:',x,w,'ro-',x,g,'c^-');
>> legend('sin(x)','cos(x)','Sigmoid','Gauss function');
