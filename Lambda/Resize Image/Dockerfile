FROM public.ecr.aws/lambda/python:3.11

RUN pip install pillow

COPY lambda_function.py ./

CMD ["lambda_function.lambda_handler"]