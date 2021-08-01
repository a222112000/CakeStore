
# CakeStore
# Project Structure

# Coroutines

|--viewmodel -> CharacterListViewModel -Used Coroutines launch for call API service and insert data into local database in a background thread.
|--MyApplication - To start Workmanager job and run in the background thread.

# ViewModel

|--viewmodel ->CharacterListViewModel - It is preparing and managing data for display Characterlist, search and filter.
|--viewmodel ->CharacterDetailViewModel - It is preparing and managing data for display selected character details.

# ViewBinding/DataBinding

|--CharacterList_Fragment - ViewBinding has been used here for resource layout, recyclerView and searchView.
Databinding has been used for bind UI components of row_characters.xml and fragment_chardetail.xml with data source.

# Retrofit2

|--di -> NetworkModule - Retrofit has been used to perform network calls
# GSON

|--di -> NetworkModule - Gson has been used for json data parsing.

# Picasso

|--util ->BindingAdapters - Here, Picasso image loading library has been used to load image into imageview.

# Architecture

This app uses MVVM (Model View View-Model) architecture.

https://user-images.githubusercontent.com/58938625/91903352-ff443400-ec9a-11ea-8fd0-853d6336bcf4.png
