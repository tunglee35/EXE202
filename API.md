# Nano Gradient AI Documentation

## Introduction

Welcome to the Nano Gradient AI documentation! This document will provide a comprehensive guide on how to use different APIs offered by Whisper AI to help you develop intelligent voice assistants.

## API List

### Speech-to-Text API

The Speech-to-Text API allows you to convert speech to text, making it easier to process and analyze user input. To use this API, simply send an audio file to the API endpoint, and the API will return the text transcription of the audio.

**Endpoint:** `/speech-to-text`

**Request Method:** `POST`

**Request Parameters:**

| Parameter | Required | Description |
| --- | --- | --- |
| audio_file | Yes | The audio file to be transcribed. |

**Response:**

The API will return a JSON object containing the text transcription of the audio file.

### Text-to-Speech API

The Text-to-Speech API allows you to generate human-like speech from text. This API is useful for creating voice responses for your voice assistant. To use this API, simply send text to the API endpoint, and the API will return an audio file of the generated speech.

**Endpoint:** `/text-to-speech`

**Request Method:** `POST`

**Request Parameters:**

| Parameter | Required | Description |
| --- | --- | --- |
| text | Yes | The text to be converted to speech. |

**Response:**

The API will return an audio file of the generated speech.

### Natural Language Processing API

The Natural Language Processing API allows you to analyze and understand user input. This API can identify the intent behind user input and extract relevant information. To use this API, send user input to the API endpoint, and the API will return the identified intent and extracted information.

**Endpoint:** `/nlp`

**Request Method:** `POST`

**Request Parameters:**

| Parameter | Required | Description |
| --- | --- | --- |
| text | Yes | The user input to be analyzed. |

**Response:**

The API will return a JSON object containing the identified intent and extracted information.

## Getting Started

To get started with Whisper AI, sign up for an API key on our website. Once you have an API key, you can start using our APIs to develop your voice assistant.

## API Documentation

For detailed documentation on how to use each API, please refer to our API documentation on our website.

## Support

If you need any help or support while using Whisper AI, please contact our support team at [support email]. We are always happy to help!
