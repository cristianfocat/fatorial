s=1
n=int(input('Digite um número: '))
for x in range(1,n+1):
    s*=x
print(f"O fatorial de '{n}' é: {s}")
