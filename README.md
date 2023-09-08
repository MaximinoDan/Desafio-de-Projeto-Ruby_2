# Desafio-de-Projeto-Ruby_2
Desafio de Projeto - DIO,  Formação Back-end com Ruby

num = []

print ("Digite o primeiro número: ")
num.push gets.chomp.to_i

print ("Digite o segundo número: ")
num.push gets.chomp.to_i

print ("Digite o terceiro e último número: ")
num.push gets.chomp.to_i

potencia_numeros = num.map do |x|
    x ** 3
end

puts "\n Números solicitados"
puts "#{num}"

puts"\n Números elevados a 3ª Potência"
puts"#{potencia_numeros}"
